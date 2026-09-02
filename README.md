<div align="center">

<a href="https://github.com/shivvyas2">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=28&duration=3000&pause=1000&color=0EA5E9&center=true&vCenter=true&width=640&lines=Hi%2C+I'm+Shiv+Vyas;iOS+Engineer+%E2%80%A2+Full-Stack+%E2%80%A2+AI+Products;Swift+%E2%80%A2+SwiftUI+%E2%80%A2+React+Native+%E2%80%A2+Next.js" alt="Shiv Vyas: iOS engineer, full-stack, AI products" />
</a>

<br />

<p>
  <img src="https://img.shields.io/badge/Based_in-New_York-0EA5E9?style=flat-square" alt="Based in New York" />
  <img src="https://img.shields.io/badge/Focus-Native_iOS_%2B_AI-8B5CF6?style=flat-square" alt="Focus: native iOS and AI" />
  <img src="https://img.shields.io/badge/Open_to-NYC_Roles-10B981?style=flat-square" alt="Open to NYC roles" />
  <img src="https://komarev.com/ghpvc/?username=shivvyas2&label=Profile%20views&color=0EA5E9&style=flat-square" alt="Profile views" />
</p>

</div>

---

## About Me

I build mobile products end to end: native iOS in Swift and SwiftUI, cross-platform apps in React Native, web in Next.js, and the AI backends behind them. Lately most of my work runs a language model somewhere in the loop, on the device where it can and in the cloud where it must.

- Leading native iOS at **Contextual Intelligence** (formerly Luna Social), a social app with an iMessage agent behind it
- M.S. Computer Science, **Pace University**, with a focus on HCI and mobile development
- Building **Life OS**, a personal health app that reasons over Apple Watch, Whoop and Renpho data on device
- Off the clock: guitar, film photography, long-form writing

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### Life OS
*One app for every signal you already wear and carry*

Pulls Apple Watch, iPhone, Whoop and Renpho data into a single daily picture, then uses Apple's on-device Foundation Models to say what is working and what is not. Local-first with a Supabase sync layer and a cloud coach for the questions the phone cannot answer alone.

**Stack:** Swift 6 · SwiftUI · Foundation Models · HealthKit · AVAudioEngine · Supabase · Cloud Run · Claude API

`#ios` `#on-device-ml` `#health` `#private`

</td>
<td width="50%" valign="top">

### Astra
*Vedic astrology readings with the math done by code, not the model*

A Next.js API and a native Swift client. Dosha and transit detection is deterministic; Claude only writes the reading. Twice-daily readings arrive over APNs on the user's own clock, prompts are split for cache reuse, and follow-up questions are generated on device by Apple Intelligence so a reading never leaves the phone.

**Stack:** Next.js · TypeScript · Swift · SwiftUI · Claude API · Supabase · APNs · Sign in with Apple

`#ios` `#full-stack` `#llm` `#private`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Slipie](https://github.com/shivvyas2/Sleepie)
*Sleep tracking with adaptive soundscapes, iPhone and Apple Watch*

Real-time audio built on an AVAudioEngine node graph with synthesized PCM, running in the background through the night. Watch biometrics arrive over WatchConnectivity, a sleep-stage classifier turns them into stages, and sessions sync to Supabase.

**Stack:** Swift · SwiftUI · watchOS · AVAudioEngine · HealthKit · WatchConnectivity · Supabase

`#ios` `#watchos` `#audio`

</td>
<td width="50%" valign="top">

### [WhyKnot](https://github.com/shivvyas2/WHYKNOT)
*Where should a restaurant open next? Ask the order data.*

Hackathon build on Knot's Transaction Link. Diners connect DoorDash and Uber Eats for rewards; operators see a demand heatmap of what people already order in areas nobody serves. [Live demo](https://whyknot.vercel.app) · [Walkthrough](https://www.youtube.com/watch?v=k9Om6UzmQh0)

**Stack:** Next.js · TypeScript · Knot API · Supabase · Vercel

`#web` `#fintech` `#hackathon`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Contextual Intelligence *(iOS)*
*Leading the native SwiftUI app at work*

End-to-end ownership of a production social app: architecture, media playback and caching, Combine pipelines, UIKit bridging where SwiftUI runs out, and performance work across a 500-file codebase with a 15-person history.

**Stack:** Swift · SwiftUI · Combine · AVFoundation · Firebase

`#ios` `#swiftui` `#work`

</td>
<td width="50%" valign="top">

### Luna Agents
*An agent that lives in iMessage*

Backend for Clo, the Contextual Intelligence assistant. iMessage webhooks flow through deterministic handlers for consent and RSVPs, then into a LangGraph agent with tools for reservations, events, people matching and rides. Background workers handle proactive outreach and profile embeddings.

**Stack:** Python · FastAPI · LangGraph · Gemini · Redis · Firestore · Composio

`#agents` `#backend` `#work`

</td>
</tr>
</table>

<div align="center">
  <sub>Earlier work: <a href="https://github.com/shivvyas2/Inhale-Breathing-App">Inhale</a> (guided breathing, React Native) · Day Guide (calendar and email through a Gemini chat, React Native) · <a href="https://github.com/shivvyas2/ExpenseTracker--iOS">Expense Tracker</a> (SwiftUI) · <a href="https://github.com/shivvyas2/SATistics">SATistics</a> (arcade-style SAT practice) · <a href="https://github.com/shivvyas2/shivvyas.com">shivvyas.com</a> (Next.js and Three.js)</sub>
</div>

---

## Journey

```mermaid
timeline
    title My Path So Far
    2022 : Started M.S. in Computer Science at Pace University
         : First deep dive into HCI and mobile development
    2023 : Shipped Ghor Kalyug and Calm Pulse on Android
         : Kotlin, Jetpack, Firebase
    2024 : Lead Mobile Developer at Futeur AI, React Native and cross-platform architecture
         : Joined Luna Social in December to lead the native SwiftUI iOS app
    2025 : Shipped Day Guide (React Native, Gemini, FastAPI) and Slipie (iOS and watchOS)
         : Fintech web platforms for Futeur AI in Next.js
    2026 : Luna Social became Contextual Intelligence, with Luna Agents shipping over iMessage
         : Building Life OS and Astra, on-device LLMs with Claude in the loop
```

---

## Tech I Reach For

<div align="center">

**Mobile**
<p>
  <img src="https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white" alt="Swift" />
  <img src="https://img.shields.io/badge/SwiftUI-0C74D7?style=for-the-badge&logo=swift&logoColor=white" alt="SwiftUI" />
  <img src="https://img.shields.io/badge/Combine-000000?style=for-the-badge&logo=apple&logoColor=white" alt="Combine" />
  <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React Native" />
  <img src="https://img.shields.io/badge/Expo-1B1F23?style=for-the-badge&logo=expo&logoColor=white" alt="Expo" />
</p>

**Web**
<p>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel" />
</p>

**AI & Backend**
<p>
  <img src="https://img.shields.io/badge/Claude_API-D97706?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude API" />
  <img src="https://img.shields.io/badge/Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Gemini" />
  <img src="https://img.shields.io/badge/Foundation_Models-000000?style=for-the-badge&logo=apple&logoColor=white" alt="Apple Foundation Models" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangGraph" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" />
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="Google Cloud" />
</p>

</div>

---

## GitHub Snapshot

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=shivvyas2&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=0EA5E9&icon_color=8B5CF6&text_color=FFFFFF" height="165" alt="GitHub stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=shivvyas2&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=0EA5E9&text_color=FFFFFF&langs_count=6" height="165" alt="Top languages" />

</div>

---

## Currently

<table>
<tr>
<td>

- **Building** Life OS and Astra, two apps where the model runs on the phone whenever it can
- **Shipping** the Contextual Intelligence iOS app and the iMessage agent behind it
- **Learning** Swift 6 strict concurrency, Foundation Models, and how to keep LLM features cheap enough to ship an app for free
- **Open to** iOS and full-stack roles in NYC
- **Reach me** at [shivvyas0209@gmail.com](mailto:shivvyas0209@gmail.com)

</td>
</tr>
</table>

---

## Let's Connect

<div align="center">

<a href="https://www.linkedin.com/in/shivvyas/">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="https://shivvyas.com">
  <img src="https://img.shields.io/badge/shivvyas.com-0EA5E9?style=for-the-badge&logo=safari&logoColor=white" alt="Website" />
</a>
<a href="mailto:shivvyas0209@gmail.com">
  <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>
<a href="https://dev.to/shivvyas2">
  <img src="https://img.shields.io/badge/dev.to-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white" alt="dev.to" />
</a>
<a href="https://www.instagram.com/shivvyas_/">
  <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
</a>
<a href="https://www.youtube.com/@ShivVyas">
  <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" />
</a>
<a href="https://leetcode.com/shivvyas_/">
  <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" />
</a>

</div>

<div align="center">
  <sub>Built with care in New York. Always learning, always shipping.</sub>
</div>
