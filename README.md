
<h1 align="center">LUXORA AI</h1>

<div align="center">

LUXORA AI is a web-based immersive luxury retail platform designed to explore how augmented reality and behavioural analytics can enhance digital luxury shopping. It combines interactive 3D product visualization, voice-controlled navigation, product storytelling, behavioural analytics, and ML to create an immersive luxury retail experience.

</div>

## Live Project

**[Launch LUXORA AI](https://luxora-ai.pages.dev/)** ··· **[View Analytics Dashboard](https://luxora-ar-dashboard.vercel.app/)**

<b> Users can: </b>

- Explore luxury products through interactive 3D visualization
- Navigate products using voice commands
- Explore product journeys and provenance stories
- Save products and interact with their selections

## System Architecture

```text
                    ┌─────────────────────┐
                    │     LUXORA AI       │
                    │   Web Application   │
                    └──────────┬──────────┘
                               │
              ┌────────────────┼────────────────┐
              │                │                │
              ▼                ▼                ▼
        3D Product       Voice Interface    User Events
        Visualization    Web Speech API     & Feedback
              │                │                │
              └────────────────┼────────────────┘
                               ▼
                    ┌─────────────────────┐
                    │      Supabase       │
                    │   PostgreSQL Data   │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │  Analytics Dashboard│
                    │       Vercel        │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │    ML Analysis      │
                    │    & Prediction     │
                    └─────────────────────┘
```

## Technology Stack

<table>
<tr>
<td> <b>Frontend</b> </td>
<td> React · Vite · Tailwind CSS · Framer Motion </td>
</tr>
<tr>
<td> <b> 3D / AR </b> </td>
<td> Three.js · React Three Fiber · React Three Drei · GLB · Draco </td>
</tr>
<tr>
<td> <b> Voice Interface </b> </td>
<td> Web Speech API</td>
</tr>
<tr>
<td> <b> Data & Backend </b> </td>
<td> Supabase · PostgreSQL </td>
</tr>
<tr>
<td> <b> Analytics & ML </b> </td>
<td> Python · pandas · scikit-learn · TextBlob </td>
</tr>
<tr>
<td> <b> Deployment </b> </td>
<td> Cloudflare Pages · Vercel </td>
</tr>
</table>

## Behavioural Analytics

<b> The system tracks interactions such as: </b> <code>Product Rotation</code> · <code>Zoom</code> · <code>Product Switching</code> ·
  <code>Journey Views</code> ·
  <code>Category Filtering</code> ·
  <code>Voice Commands</code> ·
  <code>Add to Cart</code> ·
  <code>Ratings</code> ·
  <code>Checkout Completion</code>
</p>

## Machine Learning

> The project explores whether behavioural interactions within an immersive retail environment can be used to predict cart conversion. Models evaluated include:

`Logistic Regression` ··· `Random Forest`

The Random Forest model achieved a reported **81.3%** accuracy and **0.746** AUC on the project's evaluation dataset.

## Project Results

<table align="center">
  <tr>
    <th>Metric</th>
    <th>Result</th>
  </tr>
  <tr>
    <td align="center"><b>User sessions</b></td>
    <td align="center">79</td>
  </tr>
  <tr>
    <td align="center"><b>Interaction events</b></td>
    <td align="center">4,437</td>
  </tr>
  <tr>
    <td align="center"><b>Feedback submissions</b></td>
    <td align="center">24</td>
  </tr>
  <tr>
    <td align="center"><b>Average rating</b></td>
    <td align="center">4.6 / 5</td>
  </tr>
  <tr>
    <td align="center"><b>Cart conversion</b></td>
    <td align="center">29.1%</td>
  </tr>
  <tr>
    <td align="center"><b>Random Forest accuracy</b></td>
    <td align="center">81.3%</td>
  </tr>
  <tr>
    <td align="center"><b>Random Forest AUC</b></td>
    <td align="center">0.746</td>
  </tr>
</table>

---

<div align="center">
  
  #### Authors: Narda Zaria and Valiveti Aiswarya

  </div>

<p align="center">⋆｡°✩｡°⋆</p>

<div align="center">
<sub>
  Note: These results are based on the project's prototype evaluation dataset collected from real interactions of prototype users.
</sub>
</div>
