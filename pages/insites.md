---
type: page
title: Insites
date: 2020-01-03
description: Interesting, inspirational, insightful interfaces and interactions. By Shu Ding.
---

# Insites

Interesting, inspirational, insightful interfaces and interactions.

export function Insite({ title, url, description }) {
  const H3 = 'h3'
  return (
    <a className="insite-card block font-semibold" href={url} target="_blank">
      <H3>
        {title}
      </H3>
      <p>{description}</p>
    </a>
  );
}

<div style={{ display: 'flex', gap: '1rem', flexWrap: 'wrap' }}>
  <Insite title="CSS-Only Dino Game" url="/insites/dino.html" description="A trick to reflect document state from CSS animations (Chrome only)." />
  <Insite title="Deutsch.css" url="/insites/deutsch-css" description="Translate any website into Deutsch." />
  <Insite title="Void" url="/insites/void" description="An interactive game (desktop only)." />
</div>
