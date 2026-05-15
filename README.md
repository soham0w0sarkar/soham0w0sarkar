<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0f0f,100:1a1a2e&height=120&section=header&text=Soham%20Sarkar&fontSize=42&fontColor=e0e0e0&fontAlignY=65&desc=backend%20engineer%20%20%7C%20%20i%20build%20things%20and%20break%20them%20to%20understand%20why&descSize=13&descAlignY=85&descColor=888888" />
</div>

<br/>

<table>
<tr>
<td width="55%" valign="top">

### the war stories

**port exhaustion. 1.5 seconds.**

Hit my load balancer with k6. 95% failure rate. Traced it to `MaxIdleConnsPerHost: 2` — Go's default. 28,000 ephemeral ports exhausted before I blinked.

One config change. **8.2M successful requests.** p95 latency: 359ms → 43ms.

→ [the debugging writeup](https://medium.com/@sohamsarkar59/part-2-from-port-exhaustion-to-8-2m-requests-debugging-a-production-performance-issue-2c5175e09660)

---

**building a CRDT engine because I wanted to understand how Figma works**

Skip list for O(log n) indexing. Tombstone deletion. State vector sync. Transport agnostic. It's called Relay and it's half done and I'm learning more from it than anything else.

→ [Relay](https://github.com/soham0w0sarkar/Relay)

</td>
<td width="45%" valign="top" align="center">

<img src="https://media.giphy.com/media/JIX9t2j0ZTN9S/giphy.gif"  />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=soham0w0sarkar&theme=transparent&hide_border=true&ring=58a6ff&fire=58a6ff&currStreakLabel=e0e0e0&sideLabels=888888&dates=555555" />

</td>
</tr>
</table>

---

### what I actually use

<p>
  <img src="https://skillicons.dev/icons?i=go,ts,js,python,c,cpp&theme=dark" />
</p>
<p>
  <img src="https://skillicons.dev/icons?i=redis,postgres,mongodb,docker,kubernetes,gcp&theme=dark" />
</p>
<p>
  <img src="https://skillicons.dev/icons?i=linux,git,grafana,prometheus&theme=dark" />
</p>

---

### by the numbers

```
8.2M      requests handled in a single k6 run
95% → 7%  failure rate after debugging port exhaustion
200ms     p95 latency on Redis pub/sub pipelines built in production
2         data structures implemented from scratch (skip list + CRDT)
1         fun fact: I like mango
```

---

### currently

- 🔧 Finishing **Relay** — CRDT collab engine in TypeScript
- 📖 Learning distributed systems correctness and networking internals
- 🌍 Open to **remote backend roles** — Go, distributed systems, infra
- 📬 [sohamsarkar59@gmail.com](mailto:sohamsarkar59@gmail.com) · [LinkedIn](https://linkedin.com/in/sohamsarkar) · [Twitter](https://twitter.com/avgdevexp) · [Medium](https://medium.com/@sohamsarkar59)

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,100:0f0f0f&height=80&section=footer" />
</div>
