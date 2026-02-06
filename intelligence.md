---
layout: default
title: The Briefing
---

<section class="section-pad">
  <div style="max-width: 800px; margin: 0 auto;">
    <h1 style="font-size: 3rem; font-weight: normal; color: #1a1a1a; margin-bottom: 10px;">The Briefing</h1>
    <p style="color: #666; font-style: italic; margin-bottom: 60px; font-size: 1.1rem;">Proprietary intelligence for the $1.8M+ transition in Surrey’s premium enclaves.</p>

    {% for post in site.posts %}
    <div style="border-bottom: 1px solid #eee; padding: 40px 0;">
        <span style="font-size: 0.7rem; text-transform: uppercase; letter-spacing: 2px; color: #999;">{{ post.date | date: "%b %d, %Y" }}</span>
        <h3 style="font-size: 1.5rem; font-weight: normal; margin: 10px 0;">
            <a href="{{ post.url }}" style="color: #1a1a1a; text-decoration: none;">{{ post.title }}</a>
        </h3>
        <p style="color: #444;">{{ post.excerpt | strip_html | truncatewords: 25 }}</p>
        <a href="{{ post.url }}" style="font-size: 0.8rem; font-weight: bold; text-transform: uppercase; letter-spacing: 1px; color: #1a1a1a; text-decoration: none; border-bottom: 2px solid #1a1a1a;">Read Analysis →</a>
    </div>
    {% endfor %}

  </div>
</section>
