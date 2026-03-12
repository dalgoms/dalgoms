# CRO Strategy 2025

**Data-Driven Website UX & Conversion Rate Optimization Strategy**

> sorizava.com · From quantitative expansion to qualitative optimization

---

## Situation at a Glance

```mermaid
flowchart LR
    subgraph good ["Quantitative Growth"]
        A["Sessions 3.16M\n+104%"]
        B["Form Submissions 17,063\n+1,078%"]
    end
    subgraph bad ["Qualitative Concern"]
        C["Bounce Rate 91%\n+2%p"]
        D["Session Duration 2m 23s\n-33%"]
    end
    A -.->|"Growth Paradox"| C
    B -.->|"Sustainable?"| D
```

| Metric | Value | YoY | Signal |
|---|---:|---|:---:|
| Sessions | 3.16M | +104% | + |
| Unique Visitors | 2.22M | +92% | + |
| Form Submissions | 17,063 | +1,078% | + |
| Bounce Rate | 91.0% | +2%p | - |
| Avg Session Duration | 2m 23s | -33% | - |
| Pages per Session | 1.1 | — | - |

**Core Diagnosis:** The quantitative explosion of 2025 was a media optimization victory. The next challenge is clear — **qualitative refinement of the conversion structure** to capture the 91% of prospects currently bouncing.

---

## 1. User Behavior Data Deep Dive

### Traffic Inflow vs Conversion Efficiency

```mermaid
flowchart TD
    subgraph inflow ["Inflow (Paid)"]
        FB["Facebook Paid Search\n937K"]
        IG["Instagram Paid Search\n830K"]
    end
    subgraph landing ["Landing"]
        LP["/livesteno\n1.12M Sessions"]
    end
    subgraph outcome ["Outcome"]
        STAY["Next Step\n93K (8%)"]
        BOUNCE["Immediate Exit\n1.03M (92%)"]
    end

    FB --> LP
    IG --> LP
    LP --> STAY
    LP --> BOUNCE
```

| Segment | Volume | Interpretation |
|---|---:|---|
| Paid Ads → Landing | 1.77M | Meta media optimization success |
| Landing → Engaged | ~93K (8%) | Site experience delivery failure |
| Landing → Bounced | ~1.03M (92%) | Marketing ROI leakage |
| Engaged → Converted | 17,063 | Conversion structure itself works |

> +1,078% conversions are a success of media-landing alignment. The next leverage is **capturing additional conversion opportunities** from the 91% bounce segment.

---

## 2. Device Environment Analysis

### Extreme Mobile Dominance

```mermaid
pie title Session Share by Device
    "Mobile 98%" : 309.5
    "Desktop 2%" : 5.3
    "Tablet 0%" : 1.5
```

| Device | Sessions | Share |
|---|---:|---:|
| Mobile | 3.10M | **98%** |
| Desktop | 53K | 2% |
| Tablet | 15K | 0% |

### Strategic Assessment

> Building mobile-only landing pages for the 98% mobile environment was the foundation of 10x conversion growth. The next step is redefining the entire remaining UI to a **mobile-only** standard.

```mermaid
flowchart LR
    A["Current: Responsive"] -->|"Transition"| B["Target: Mobile-Only"]
    B --> C["Thumb-Zone CTA Placement"]
    B --> D["Font & Infographic Readability"]
    B --> E["Minimize Form Steps"]
```

---

## 3. User Navigation Bottleneck Analysis

### The Main Leak: /livesteno

```mermaid
flowchart TD
    subgraph entry ["Entry"]
        AD["Paid Ad Click"]
    end
    subgraph page1 ["/livesteno"]
        VIEW["1.12M Sessions\n1.23M Views"]
    end
    subgraph split ["Split"]
        NEXT["Next Page\n~93K\n(10%)"]
        EXIT["Immediate Exit\n1.03M\n(90%)"]
    end
    subgraph convert ["Conversion"]
        FORM["Form Submission"]
    end

    AD --> VIEW
    VIEW --> NEXT
    VIEW --> EXIT
    NEXT --> FORM
```

### Bottleneck Diagnosis

| Problem | Data | Meaning |
|---|---|---|
| Single page consumption | 1.1 pages/session | Users leave after viewing one page |
| No narrative | No next-step suggestion | Failed to sustain engagement |
| Information island | /livesteno isolated | 1.23M views not connecting to conversions |

> /livesteno successfully concentrated 1.12M sessions as an anchor page. The key to next-stage growth is **stitching** this traffic to the next step.

---

## 4. Site Narrative Redesign

### Current vs Target UX Flow

```mermaid
flowchart LR
    subgraph now ["AS-IS"]
        A1["Ad Click"] --> A2["Landing Arrival"]
        A2 --> A3["Information Dump"]
        A3 --> A4["91% Exit"]
    end
```

```mermaid
flowchart LR
    subgraph future ["TO-BE"]
        B1["Ad Click"] --> B2["Pain Point Empathy"]
        B2 --> B3["Solution Presentation"]
        B3 --> B4["Social Proof"]
        B4 --> B5["CTA"]
    end
```

### Narrative Redesign Framework

| Stage | Current | Improvement | Expected Effect |
|---|---|---|---|
| 1. Entry | Information dump | Pain Point empathy headline | Scroll engagement |
| 2. Exploration | No next step | Solution + Social Proof sequence | Increased dwell time |
| 3. Conversion | Unclear CTA position | Fixed CTA within Thumb-Zone | Higher conversion rate |
| 4. Connection | Pages disconnected | /livesteno → /hello bridge design | More pages per session |

### Session Duration Recovery Strategy

```mermaid
flowchart LR
    A["/livesteno"] -->|"Strategic Bridge"| B["/hello"]
    A -->|"Related Content"| C["/start"]
    A -->|"Related Content"| D["/adstenostart"]
    B --> E["Form Submission\nConversion"]
```

---

## 5. Conversion Maximization: CTA Optimization

### Proven Success Formula

| CTA | Location | Clicks | Conversion Power |
|---|---|---:|---|
| Apply Now | /hello | **9,100** | Strongest |
| Purchase | /sorizavakeyboard | **5,417** | High |
| Purchase | /sorizavakeyboard | **5,106** | High |
| Apply Now | /helloo | **3,911** | Medium-High |
| Purchase | /sorizavakeyboard | **3,915** | Medium-High |

### CTA Transplant Strategy

```mermaid
flowchart TD
    subgraph proven ["Proven CTAs (Source: /hello)"]
        CTA1["'Apply Now'\n9,100 clicks"]
        CTA2["'Purchase'\n14,000+ clicks"]
    end
    subgraph target ["Transplant Targets"]
        T1["/livesteno\n1.12M sessions\n→ 1.03M bounced"]
        T2["All Anchor Pages"]
    end
    subgraph result ["Expected Result"]
        R1["Bounced Users → Conversion Opportunities"]
    end

    CTA1 --> T1
    CTA2 --> T2
    T1 --> R1
    T2 --> R1
```

### Frictionless Form Design Principles

| Principle | Execution |
|---|---|
| Minimize input steps | Expose only required fields, leverage autofill |
| Show progress | Step indicators to give completion sense |
| Mobile keyboard optimization | Appropriate keyboard type per input field |
| Prevent mid-form abandonment | Auto-save form data on exit |

---

## 6. Execution Roadmap

### 3 Core Initiatives

```mermaid
flowchart TD
    subgraph p1 ["Phase 1: Immediate"]
        A["Mobile-First UI Transition\n98% user coverage"]
    end
    subgraph p2 ["Phase 2: Within 4 Weeks"]
        B["Narrative Restructure\n/livesteno 1.03M bounced → conversion"]
    end
    subgraph p3 ["Phase 3: Within 8 Weeks"]
        C["CTA Optimization Rollout\n/hello success formula expansion"]
    end

    A --> B --> C
```

### Initiative Details

| Initiative | Key Action | Target Metric | Expected Impact |
|---|---|---|---|
| Mobile First | Deprecate desktop UI, Thumb-Zone CTA | Bounce rate 91% → below 80% | Mobile conversion rate increase |
| Narrative Restructure | /livesteno → /hello bridge, storytelling flow | Pages/session 1.1 → 2.0+ | Session duration recovery |
| CTA Rollout | 'Apply Now' button site-wide, Frictionless forms | +30% additional form submission growth | ROI maximization |

### Projected Impact on Success

```mermaid
flowchart LR
    subgraph before ["Current"]
        B1["Bounce Rate 91%"]
        B2["Session Duration 2m 23s"]
        B3["Pages/Session 1.1"]
    end
    subgraph after ["Target"]
        A1["Bounce Rate below 80%"]
        A2["Session Duration 3m 30s+"]
        A3["Pages/Session 2.0+"]
    end
    B1 -->|"-11%p"| A1
    B2 -->|"+47%"| A2
    B3 -->|"+82%"| A3
```

---

## Conclusion

The direction the data points to is clear.

**The era of quantitative expansion is over. It's time for qualitative optimization.**

3.16M sessions and 17,063 conversions were the victory of media optimization and anchor page strategy. Building on this success, transplanting the proven CTA strategy from /hello to /livesteno, transitioning to mobile-only UX, and connecting inter-page narratives — these three are the next leverage points to structurally scale current performance.

---

*Growth Marketing Lead · Seyoung Lee · [Performance Report](2025-website-performance-en.md) · [Back to README](../README_EN.md)*
