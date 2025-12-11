🏠 Homepage Layout Customization – Demo Presentation

## 📖 Description

This document highlights the new customizable homepage experience available in Depo.
Using Backstage’s `CustomHomepageGrid` and our extended UI tooling, end-users can now personalize their homepage by rearranging, resizing, and configuring widgets to fit their workflow.

These improvements give every developer, analyst, and engineer a dashboard that reflects their needs, not a one-size-fits-all layout.

### 💻 Typical Use Cases

- **Personal dashboards**

    Users build their own overview: recent PRs, CI status, alerts, KPIs, etc.

- **Team-focused homepages**

    Each squad can tailor the layout to show its own systems, incidents, deployments, and dashboards.

- **Productivity shortcuts**

    Bring quick links, documentation, or tools to the top for faster daily navigation.

- **Monitoring & insights**

    Resize larger widgets (Grafana, builds, logs, PR boards) to get more visibility.


## 🎯 Features Added

### ↔️ Resizable Widgets

Users can grab the bottom-right corner of any card to resize it:
- Make dashboards widgets wider
- Compress smaller utility widgets
- Create asymmetric but functional layouts
- All size changes persist in the user profile

→ Large data? Make the card big. Small shortcut? Shrink it.

### 🧩 Drag & Drop Widget Customization

Widgets (InfoCards) can now be freely moved around the homepage:
- Click + drag a card to reposition it
- The layout automatically recalculates spacing, grid alignment and collisions
- The new order is saved so the user sees the same layout next time

→ This gives users full control over how their homepage is structured.

### ⚙️ Settings-Based Customization

We added a clean, consistent overlay for modifying widget configuration. Each widget can optionally expose its own Settings panel, allowing users to modify:
 
→ Goodbye static homepage. Hello personalized experience.

### 🧱 Persisted Per-User Layout Storage

All layout changes—positions, sizes, hidden cards—are saved:

- Stored in the browser's local storage
- Persist across page refreshes, logouts, and browser restarts

→ Your homepage stays yours.

### 🎛️ Updated UI Components & Better Developer Experience

- Unified grid engine built around CustomHomepageGrid
- Predictable card behavior: snapping, spacing, min/max sizes

→ Feature teams can now integrate homepage cards faster and with zero boilerplate.

## 🚀 Ideas for Future Improvements

- **Synced across devices**

    Right now the layout is stored in local storage. Sync it to the user profile in the backend.

- **Preset layouts**

    Allow switching between “Developer”, “Ops”, “Manager”, “Minimalistic”, etc.

- **Shareable layouts**

    Users can export & share their homepage setups with their teams.

- **Team-level default layouts**

    Squads can standardize the homepage for onboarding.

- **Conditional widgets**

    Show specific cards only when certain systems have incidents.

- **Multi-tab homepages**

    Create separate tabs like “My Tools”, “Monitoring”, “Delivery”, “Insights”.


## Q & A

![Q&A](assets/any-questions.png)
