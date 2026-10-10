import React from "react";

const stats = [
  { value: "99.98%", label: "Platform uptime" },
  { value: "3.4x", label: "Faster deployment cycles" },
  { value: "24/7", label: "Global monitoring coverage" },
  { value: "150+", label: "Enterprise integrations" },
];

const features = [
  {
    title: "Unified system control",
    text: "Monitor infrastructure, automate tasks, and coordinate resources from one operational layer.",
    badge: "01",
  },
  {
    title: "Predictive intelligence",
    text: "Analyze operating trends to catch anomalies before they become service interruptions.",
    badge: "02",
  },
  {
    title: "Secure-by-default",
    text: "Role-based access, end-to-end encryption, and policy controls embedded at every layer.",
    badge: "03",
  },
  {
    title: "AI workflow orchestration",
    text: "Design intelligent workflows that adapt to demand, risk, and critical business priorities.",
    badge: "04",
  },
  {
    title: "Cross-platform operations",
    text: "Run your stack across cloud, edge, and hybrid environments with the same control plane.",
    badge: "05",
  },
  {
    title: "Enterprise observability",
    text: "Collect actionable system signals and convert them into decisions, not dashboards alone.",
    badge: "06",
  },
];

const solutions = [
  "Cloud architecture",
  "Systems automation",
  "Unified observability",
  "Infrastructure security",
  "Data orchestration",
  "Business continuity",
];

const testimonials = [
  {
    quote:
      "Technologic gave our operations team a real-time control layer that reduced response time and improved reliability across every service.",
    author: "Lena Moore",
    role: "VP of Infrastructure, Northstar Labs",
  },
  {
    quote:
      "The platform feels like a command center for our digital business—clear, intelligent, compact, and resilient.",
    author: "Daniel Ross",
    role: "Director of Digital Systems, QuantaWorks",
  },
];

const plans = [
  {
    name: "Starter",
    price: "$49",
    description: "For lean teams optimizing their first resilient digital workflows.",
    features: ["Core monitoring", "3 systems connected", "Basic automation", "Email support"],
    featured: false,
  },
  {
    name: "Growth",
    price: "$129",
    description: "For scaling organizations that need more control and visibility.",
    features: ["Full observability", "Unlimited alerts", "AI automation", "Priority support"],
    featured: true,
  },
  {
    name: "Enterprise",
    price: "Custom",
    description: "For mission-critical environments with specialized security and governance.",
    features: ["Private deployment", "Custom integrations", "SLA coverage", "Dedicated success team"],
    featured: false,
  },
];

export default function TechnologicLanding() {
  return (
    <div className="techsite">
      <style>{`
        :root {
          --bg: #06131d;
          --bg-soft: #0d1e2a;
          --panel: rgba(13, 30, 42, 0.75);
          --panel-strong: #112a3a;
          --card: #0e2331;
          --card-2: #132f40;
          --text: #edf7ff;
          --muted: #a8c4d8;
          --line: rgba(170, 210, 234, 0.14);
          --accent: #7de7ff;
          --accent-2: #62f3c8;
          --accent-3: #8a7dff;
          --warning: #ffc857;
          --shadow: 0 24px 80px rgba(0, 0, 0, 0.35);
        }

        * { box-sizing: border-box; }
        html { scroll-behavior: smooth; }
        body {
          margin: 0;
          font-family: Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
          background:
            radial-gradient(circle at top left, rgba(125, 231, 255, 0.12), transparent 30%),
            radial-gradient(circle at right center, rgba(98, 243, 200, 0.1), transparent 28%),
            var(--bg);
          color: var(--text);
        }

        a { color: inherit; text-decoration: none; }
        img { max-width: 100%; display: block; }
        button { font: inherit; }

        .techsite {
          min-height: 100vh;
          color: var(--text);
        }

        .container {
          width: min(1200px, calc(100% - 32px));
          margin: 0 auto;
        }

        .topbar {
          position: sticky;
          top: 0;
          z-index: 20;
          backdrop-filter: blur(14px);
          background: rgba(6, 19, 29, 0.7);
          border-bottom: 1px solid var(--line);
        }

        .nav {
          display: flex;
          align-items: center;
          justify-content: space-between;
          min-height: 78px;
          gap: 20px;
        }

        .brand {
          display: inline-flex;
          align-items: center;
          gap: 12px;
          font-weight: 800;
          letter-spacing: 0.08em;
          text-transform: uppercase;
        }

        .brand-mark {
          width: 38px;
          height: 38px;
          border-radius: 12px;
          display: grid;
          place-items: center;
          background: linear-gradient(135deg, var(--accent), var(--accent-2));
          color: #06131d;
          font-size: 1.1rem;
          box-shadow: 0 12px 24px rgba(125, 231, 255, 0.35);
        }

        .nav-links {
          display: flex;
          align-items: center;
          gap: 28px;
          color: var(--muted);
          font-size: 0.96rem;
        }

        .nav-links a:hover { color: var(--text); }

        .nav-actions {
          display: flex;
          align-items: center;
          gap: 14px;
        }

        .btn {
          display: inline-flex;
          align-items: center;
          justify-content: center;
          border: 1px solid transparent;
          border-radius: 999px;
          padding: 0.9rem 1.35rem;
          font-weight: 700;
          transition: 180ms ease;
          cursor: pointer;
        }

        .btn:hover { transform: translateY(-1px); }

        .btn-primary {
          background: linear-gradient(135deg, var(--accent), var(--accent-2));
          color: #06212d;
          box-shadow: 0 18px 42px rgba(73, 220, 211, 0.3);
        }

        .btn-secondary {
          background: rgba(255,255,255,0.02);
          border-color: var(--line);
          color: var(--text);
        }

        .hero {
          padding: 86px 0 56px;
        }

        .hero-grid {
          display: grid;
          grid-template-columns: 1.1fr 0.9fr;
          gap: 42px;
          align-items: center;
        }

        .eyebrow {
          display: inline-flex;
          align-items: center;
          gap: 10px;
          background: rgba(125, 231, 255, 0.08);
          border: 1px solid rgba(125, 231, 255, 0.2);
          color: var(--accent);
          border-radius: 999px;
          padding: 0.5rem 0.8rem;
          font-size: 0.75rem;
          letter-spacing: 0.08em;
          text-transform: uppercase;
          font-weight: 700;
        }

        .eyebrow::before {
          content: "";
          width: 8px;
          height: 8px;
          border-radius: 50%;
          background: linear-gradient(135deg, var(--accent), var(--accent-2));
          box-shadow: 0 0 14px rgba(125, 231, 255, 0.8);
        }

        h1 {
          margin: 18px 0 16px;
          font-size: clamp(2.9rem, 6vw, 5rem);
          line-height: 0.96;
          letter-spacing: -0.07em;
        }

        .gradient-text {
          background: linear-gradient(135deg, var(--text), var(--accent), var(--accent-2));
          -webkit-background-clip: text;
          background-clip: text;
          color: transparent;
        }

        .lead {
          max-width: 620px;
          color: var(--muted);
          font-size: 1.06rem;
          line-height: 1.75;
        }

        .cta-row {
          display: flex;
          flex-wrap: wrap;
          gap: 16px;
          margin-top: 28px;
        }

        .mini-proof {
          margin-top: 28px;
          display: flex;
          flex-wrap: wrap;
          gap: 30px;
          color: var(--muted);
          font-size: 0.84rem;
        }

        .mini-proof strong {
          color: var(--text);
          font-size: 1rem;
        }

        .hero-panel {
          position: relative;
          background: linear-gradient(180deg, rgba(17, 42, 58, 0.92), rgba(10, 21, 31, 0.9));
          border: 1px solid var(--line);
          border-radius: 28px;
          padding: 22px;
          box-shadow: var(--shadow);
        }

        .status-bar {
          display: flex;
          justify-content: space-between;
          align-items: center;
          padding: 12px 14px;
          background: rgba(255,255,255,0.02);
          border: 1px solid var(--line);
          border-radius: 14px;
          color: var(--muted);
          font-size: 0.86rem;
        }

        .dot-group {
          display: flex;
          gap: 8px;
        }

        .dot {
          width: 9px;
          height: 9px;
          border-radius: 50%;
          background: var(--muted);
        }

        .dot:first-child { background: #ff6a6a; }
        .dot:nth-child(2) { background: #ffc857; }
        .dot:nth-child(3) { background: #62f3c8; }

        .dashboard {
          margin-top: 18px;
          display: grid;
          grid-template-columns: 1.2fr 0.8fr;
          gap: 18px;
        }

        .chart-box, .metric-box, .list-box {
          background: rgba(9, 19, 28, 0.8);
          border: 1px solid var(--line);
          border-radius: 18px;
        }

        .chart-box {
          padding: 20px;
          min-height: 220px;
        }

        .chart-header {
          display: flex;
          justify-content: space-between;
          align-items: center;
          margin-bottom: 18px;
          color: var(--muted);
          font-size: 0.82rem;
        }

        .bars {
          display: flex;
          align-items: end;
          justify-content: space-between;
          height: 140px;
          gap: 10px;
          margin-top: 12px;
        }

        .bar {
          flex: 1;
          border-radius: 10px 10px 0 0;
          background: linear-gradient(180deg, var(--accent), var(--accent-2));
          box-shadow: inset 0 -16px 20px rgba(255,255,255,0.08);
        }

        .bar:nth-child(1) { height: 35%; }
        .bar:nth-child(2) { height: 55%; }
        .bar:nth-child(3) { height: 68%; }
        .bar:nth-child(4) { height: 82%; }
        .bar:nth-child(5) { height: 92%; }
        .bar:nth-child(6) { height: 74%; }
        .bar:nth-child(7) { height: 100%; }

        .metric-box {
          padding: 20px;
          display: grid;
          gap: 16px;
        }

        .ring-wrap {
          display: grid;
          place-items: center;
          padding: 14px 0 8px;
        }

        .ring {
          width: 110px;
          height: 110px;
          border-radius: 50%;
          background:
            radial-gradient(circle at center, rgba(9, 19, 28, 1) 0 54%, transparent 55%),
            conic-gradient(var(--accent) 0 76%, rgba(255,255,255,0.08) 76% 100%);
          display: grid;
          place-items: center;
          color: var(--text);
          font-weight: 800;
          font-size: 1.32rem;
        }

        .mini-legend {
          display: flex;
          justify-content: space-between;
          color: var(--muted);
          font-size: 0.8rem;
        }

        .mini-legend span strong {
          color: var(--text);
        }

        .list-box {
          margin-top: 18px;
          padding: 18px 18px 8px;
        }

        .list-row {
          display: flex;
          justify-content: space-between;
          align-items: center;
          gap: 10px;
          padding: 10px 0;
          border-bottom: 1px solid var(--line);
          color: var(--muted);
          font-size: 0.86rem;
        }

        .list-row:last-child { border-bottom: 0; }

        .badge {
          padding: 0.38rem 0.6rem;
          border-radius: 999px;
          font-weight: 700;
          font-size: 0.7rem;
        }

        .badge.good {
          background: rgba(98, 243, 200, 0.12);
          color: var(--accent-2);
          border: 1px solid rgba(98,243,200,0.22);
        }

        .badge.info {
          background: rgba(125, 231, 255, 0.1);
          color: var(--accent);
          border: 1px solid rgba(125,231,255,0.22);
        }

        .stats {
          padding: 24px 0 12px;
        }

        .stats-grid {
          display: grid;
          grid-template-columns: repeat(4, minmax(0, 1fr));
          gap: 18px;
        }

        .stat-card {
          background: rgba(255,255,255,0.02);
          border: 1px solid var(--line);
          border-radius: 20px;
          padding: 28px 18px;
          text-align: center;
        }

        .stat-card strong {
          display: block;
          font-size: clamp(1.7rem, 3vw, 2.6rem);
          margin-bottom: 10px;
          letter-spacing: -0.05em;
        }

        .stat-card span {
          color: var(--muted);
          font-size: 0.9rem;
        }

        .section {
          padding: 90px 0 26px;
        }

        .section-head {
          display: flex;
          justify-content: space-between;
          align-items: end;
          gap: 18px;
          margin-bottom: 32px;
        }

        .section-head h2 {
          margin: 0;
          font-size: clamp(2.1rem, 4vw, 3rem);
          letter-spacing: -0.05em;
        }

        .section-copy {
          max-width: 560px;
          color: var(--muted);
          line-height: 1.7;
        }

        .features-grid {
          display: grid;
          grid-template-columns: repeat(3, minmax(0, 1fr));
          gap: 22px;
        }

        .feature-card {
          background: linear-gradient(180deg, rgba(13,30,42,0.82), rgba(9,19,28,0.9));
          border: 1px solid var(--line);
          border-radius: 22px;
          padding: 24px 22px;
          min-height: 230px;
          position: relative;
          overflow: hidden;
        }

        .feature-card::before {
          content: "";
          position: absolute;
          inset: 0 auto auto 0;
          width: 100%;
          height: 1px;
          background: linear-gradient(90deg, rgba(125,231,255,0.8), transparent);
          opacity: 0.8;
        }

        .feature-badge {
          display: inline-flex;
          padding: 0.42rem 0.7rem;
          border-radius: 999px;
          border: 1px solid rgba(125,231,255,0.2);
          color: var(--accent);
          background: rgba(125,231,255,0.06);
          font-size: 0.68rem;
          letter-spacing: 0.08em;
          font-weight: 800;
        }

        .feature-card h3 {
          font-size: 1.38rem;
          margin: 18px 0 12px;
          letter-spacing: -0.04em;
        }

        .feature-card p {
          margin: 0;
          line-height: 1.75;
          color: var(--muted);
        }

        .showcase {
          display: grid;
          grid-template-columns: 1fr 1fr;
          gap: 28px;
        }

        .showcase-panel {
          background: linear-gradient(180deg, rgba(13,30,42,0.9), rgba(9,19,28,0.95));
          border: 1px solid var(--line);
          border-radius: 28px;
          padding: 24px;
          box-shadow: var(--shadow);
        }

        .stack-card {
          display: grid;
          gap: 20px;
        }

        .stack-header {
          display: flex;
          align-items: center;
          justify-content: space-between;
          color: var(--muted);
          font-size: 0.82rem;
        }

        .stack-label {
          display: inline-flex;
          align-items: center;
          gap: 8px;
        }

        .stack-label::before {
          content: "";
          width: 10px;
          height: 10px;
          border-radius: 50%;
          background: var(--accent-2);
          box-shadow: 0 0 14px rgba(98,243,200,0.7);
        }

        .stack-grid {
          display: grid;
          grid-template-columns: repeat(2, minmax(0, 1fr));
          gap: 16px;
        }

        .mini-tile {
          padding: 18px;
          background: rgba(255,255,255,0.02);
          border: 1px solid var(--line);
          border-radius: 18px;
        }

        .mini-tile strong {
          display: block;
          margin-top: 12px;
          font-size: 1.05rem;
        }

        .mini-tile span {
          display: block;
          margin-top: 8px;
          font-size: 0.82rem;
          color: var(--muted);
          line-height: 1.5;
        }

        .tile-icon {
          width: 42px;
          height: 42px;
          border-radius: 12px;
          background: linear-gradient(135deg, rgba(125,231,255,0.18), rgba(138,125,255,0.18));
          display: grid;
          place-items: center;
          font-size: 1.2rem;
        }

        .process {
          display: grid;
          gap: 18px;
          margin-top: 18px;
        }

        .process-item {
          display: grid;
          grid-template-columns: 52px 1fr;
          gap: 16px;
          align-items: start;
          padding: 16px 0;
          border-bottom: 1px solid var(--line);
        }

        .process-item:last-child { border-bottom: 0; }

        .process-number {
          width: 52px;
          height: 52px;
          border-radius: 16px;
          display: grid;
          place-items: center;
          background: linear-gradient(135deg, rgba(125,231,255,0.12), rgba(98,243,200,0.12));
          border: 1px solid rgba(125,231,255,0.2);
          font-weight: 800;
          color: var(--accent);
        }

        .process-item h4 {
          margin: 0 0 8px;
          font-size: 1.12rem;
          letter-spacing: -0.03em;
        }

        .process-item p {
          margin: 0;
          color: var(--muted);
          line-height: 1.7;
        }

        .solutions-row {
          display: flex;
          flex-wrap: wrap;
          gap: 12px;
          margin-top: 20px;
        }

        .solution-pill {
          display: inline-flex;
          align-items: center;
          gap: 8px;
          padding: 0.72rem 0.9rem;
          border: 1px solid var(--line);
          border-radius: 999px;
          background: rgba(255,255,255,0.015);
          color: var(--muted);
          font-size: 0.88rem;
        }

        .solution-pill::before {
          content: "✦";
          color: var(--accent-2);
        }

        .testimonials {
          display: grid;
          grid-template-columns: repeat(2, minmax(0, 1fr));
          gap: 22px;
        }

        .quote-card {
          background: linear-gradient(180deg, rgba(13,30,42,0.82), rgba(9,19,28,0.95));
          border: 1px solid var(--line);
          border-radius: 22px;
          padding: 24px;
        }

        .quote-mark {
          font-size: 2.5rem;
          color: var(--accent);
          line-height: 1;
        }

        .quote-card p {
          margin: 18px 0 22px;
          line-height: 1.8;
          color: var(--muted);
          font-size: 1rem;
        }

        .author {
          display: flex;
          align-items: center;
          justify-content: space-between;
          gap: 14px;
        }

        .author-name {
          font-weight: 700;
        }

        .author-role {
          color: var(--muted);
          font-size: 0.8rem;
        }

        .avatar {
          width: 42px;
          height: 42px;
          border-radius: 50%;
          display: grid;
          place-items: center;
          background: linear-gradient(135deg, var(--accent), var(--accent-3));
          color: #05141c;
          font-weight: 900;
        }

        .pricing-grid {
          display: grid;
          grid-template-columns: repeat(3, minmax(0, 1fr));
          gap: 22px;
        }

        .plan-card {
          background: rgba(255,255,255,0.015);
          border: 1px solid var(--line);
          border-radius: 24px;
          padding: 24px 22px;
          position: relative;
        }

        .plan-card.featured {
          background: linear-gradient(180deg, rgba(18,44,59,0.96), rgba(12,27,37,0.96));
          border-color: rgba(125,231,255,0.35);
          box-shadow: 0 22px 60px rgba(18, 49, 59, 0.34);
        }

        .popular {
          position: absolute;
          right: 18px;
          top: 18px;
          padding: 0.38rem 0.65rem;
          border-radius: 999px;
          background: rgba(125,231,255,0.12);
          border: 1px solid rgba(125,231,255,0.2);
          color: var(--accent);
          font-size: 0.68rem;
          font-weight: 800;
          letter-spacing: 0.06em;
          text-transform: uppercase;
        }

        .plan-name {
          font-size: 1.2rem;
          font-weight: 800;
          margin-top: 4px;
        }

        .price {
          margin: 18px 0 10px;
          display: flex;
          align-items: end;
          gap: 8px;
          letter-spacing: -0.07em;
        }

        .price strong {
          font-size: 2.8rem;
        }

        .price span {
          color: var(--muted);
          font-size: 0.9rem;
          margin-bottom: 6px;
        }

        .plan-description {
          color: var(--muted);
          line-height: 1.7;
          margin-bottom: 18px;
        }

        .plan-features {
          list-style: none;
          padding: 0;
          margin: 0 0 22px;
          display: grid;
          gap: 12px;
          color: var(--muted);
        }

        .plan-features li::before {
          content: "✓";
          color: var(--accent-2);
          margin-right: 10px;
          font-weight: 900;
        }

        .cta-banner {
          margin-top: 54px;
          border-radius: 30px;
          padding: 28px 24px;
          background:
            radial-gradient(circle at left center, rgba(125,231,255,0.15), transparent 28%),
            linear-gradient(135deg, rgba(17, 42, 58, 0.9), rgba(9, 18, 28, 0.94));
          border: 1px solid var(--line);
          display: flex;
          justify-content: space-between;
          align-items: center;
          gap: 20px;
        }

        .cta-banner h3 {
          margin: 0 0 8px;
          font-size: clamp(1.7rem, 3vw, 2.5rem);
          letter-spacing: -0.05em;
        }

        .cta-banner p {
          margin: 0;
          color: var(--muted);
        }

        .footer {
          padding: 28px 0 60px;
        }

        .footer-shell {
          display: flex;
          justify-content: space-between;
          align-items: center;
          gap: 20px;
          border-top: 1px solid var(--line);
          padding-top: 24px;
          color: var(--muted);
          font-size: 0.9rem;
        }

        .footer-links {
          display: flex;
          align-items: center;
          gap: 18px;
        }

        @media (max-width: 980px) {
          .hero-grid, .showcase, .features-grid, .pricing-grid {
            grid-template-columns: 1fr;
          }

          .stats-grid {
            grid-template-columns: repeat(2, minmax(0, 1fr));
          }

          .nav-links {
            display: none;
          }
        }

        @media (max-width: 640px) {
          .cta-row, .nav-actions, .section-head, .cta-banner, .footer-shell {
            flex-direction: column;
            align-items: flex-start;
          }

          .stats-grid, .testimonials {
            grid-template-columns: 1fr;
          }

          .dashboard {
            grid-template-columns: 1fr;
          }

          h1 { font-size: 3.1rem; }
          .btn { width: 100%; }
          .cta-row > * { width: 100%; }
        }
      `}</style>

      <header className="topbar">
        <div className="container nav">
          <div className="brand">
            <div className="brand-mark">T</div>
            <span>Technologic</span>
          </div>

          <nav className="nav-links">
            <a href="#platform">Platform</a>
            <a href="#solutions">Solutions</a>
            <a href="#security">Security</a>
            <a href="#pricing">Pricing</a>
            <a href="#resources">Resources</a>
          </nav>

          <div className="nav-actions">
            <a href="#pricing" className="btn btn-secondary">Book demo</a>
            <a href="#start" className="btn btn-primary">Get started</a>
          </div>
        </div>
      </header>

      <main>
        <section className="hero">
          <div className="container hero-grid">
            <div>
              <div className="eyebrow">Trusted system intelligence</div>

              <h1>
                Build a <span className="gradient-text">smarter system</span> for modern operations.
              </h1>

              <p className="lead">
                Technologic helps teams connect infrastructure, workflows, and insights into
                a single source of control—so operations move faster, stay stable, and scale with confidence.
              </p>

              <div className="cta-row">
                <a href="#start" className="btn btn-primary">Start free trial</a>
                <a href="#platform" className="btn btn-secondary">Explore platform</a>
              </div>

              <div className="mini-proof">
                <div><strong>4.9/5</strong><br />Customer rating</div>
                <div><strong>12k+</strong><br />Connected assets</div>
                <div><strong>31%</strong><br />Lower operational cost</div>
              </div>
            </div>

            <div className="hero-panel">
              <div className="status-bar">
                <div className="dot-group">
                  <span className="dot" />
                  <span className="dot" />
                  <span className="dot" />
                </div>
                <span>Global operations overview</span>
              </div>

              <div className="dashboard">
                <div className="chart-box">
                  <div className="chart-header">
                    <span>System load</span>
                    <span className="badge good">+18.4%</span>
                  </div>

                  <div className="bars">
                    <span className="bar" />
                    <span className="bar" />
                    <span className="bar" />
                    <span className="bar" />
                    <span className="bar" />
                    <span className="bar" />
                    <span className="bar" />
                  </div>
                </div>

                <div className="metric-box">
                  <div className="ring-wrap">
                    <div className="ring">76%</div>
                  </div>
                  <div className="mini-legend">
                    <span>Health <strong>94%</strong></span>
                    <span>Alerts <strong>12</strong></span>
                  </div>
                  <div className="mini-legend">
                    <span>Latency <strong>21ms</strong></span>
                    <span>Risk <strong>Low</strong></span>
                  </div>
                </div>
              </div>

              <div className="list-box">
                <div className="list-row">
                  <span>Primary environment</span>
                  <span className="badge good">Stable</span>
                </div>
                <div className="list-row">
                  <span>Edge synchronization</span>
                  <span className="badge info">Live</span>
                </div>
                <div className="list-row">
                  <span>Automation coverage</span>
                  <span>91.6%</span>
                </div>
              </div>
            </div>
          </div>
        </section>

        <section className="stats">
          <div className="container stats-grid">
            {stats.map((stat) => (
              <div key={stat.label} className="stat-card">
                <strong>{stat.value}</strong>
                <span>{stat.label}</span>
              </div>
            ))}
          </div>
        </section>

        <section id="platform" className="section">
          <div className="container">
            <div className="section-head">
              <div>
                <div className="eyebrow">Platform overview</div>
                <h2>Everything your systems need, in one operational layer.</h2>
              </div>
              <div className="section-copy">
                Manage cloud resources, automate routine work, and make intelligent decisions with a
                system designed for scale and resilience.
              </div>
            </div>

            <div className="features-grid">
              {features.map((feature) => (
                <article key={feature.badge} className="feature-card">
                  <span className="feature-badge">{feature.badge}</span>
                  <h3>{feature.title}</h3>
                  <p>{feature.text}</p>
                </article>
              ))}
            </div>
          </div>
        </section>

        <section id="solutions" className="section">
          <div className="container">
            <div className="section-head">
              <div>
                <div className="eyebrow">Built for modern teams</div>
                <h2>Operational clarity at every layer of your business.</h2>
              </div>
              <div className="section-copy">
                From digital infrastructure to workflow automation, Technologic gives your teams a
                strong foundation for scale, governance, and growth.
              </div>
            </div>

            <div className="showcase">
              <div className="showcase-panel">
                <div className="stack-card">
                  <div className="stack-header">
                    <div className="stack-label">Deployment health</div>
                    <span className="badge good">Operational</span>
                  </div>

                  <div className="stack-grid">
                    <div className="mini-tile">
                      <div className="tile-icon">◎</div>
                      <strong>Infrastructure</strong>
                      <span>Coordinate workloads across cloud, on-prem, and edge systems.</span>
                    </div>

                    <div className="mini-tile">
                      <div className="tile-icon">⚙</div>
                      <strong>Automation</strong>
                      <span>Route tasks with event-driven logic and adaptive policies.</span>
                    </div>

                    <div className="mini-tile">
                      <div className="tile-icon">◇</div>
                      <strong>Security</strong>
                      <span>Protect every layer with policy control and built-in governance.</span>
                    </div>

                    <div className="mini-tile">
                      <div className="tile-icon">✦</div>
                      <strong>Insights</strong>
                      <span>Surface likely risks and operational opportunities before they escalate.</span>
                    </div>
                  </div>
                </div>
              </div>

              <div className="showcase-panel">
                <div className="stack-header">
                  <div className="stack-label">Execution workflow</div>
                </div>

                <div className="process">
                  <div className="process-item">
                    <div className="process-number">1</div>
                    <div>
                      <h4>Connect your systems</h4>
                      <p>Unify cloud, apps, data, and service endpoints in a single operational view.</p>
                    </div>
                  </div>

                  <div className="process-item">
                    <div className="process-number">2</div>
                    <div>
                      <h4>Trigger adaptive logic</h4>
                      <p>Build logic to respond to demand, anomalies, and growing business conditions automatically.</p>
                    </div>
                  </div>

                  <div className="process-item">
                    <div className="process-number">3</div>
                    <div>
                      <h4>Improve outcomes</h4>
                      <p>Track performance in real time and streamline decision-making across every team.</p>
                    </div>
                  </div>
                </div>

                <div className="solutions-row">
                  {solutions.map((item) => (
                    <div key={item} className="solution-pill">{item}</div>
                  ))}
                </div>
              </div>
            </div>
          </div>
        </section>

        <section id="security" className="section">
          <div className="container">
            <div className="section-head">
              <div>
                <div className="eyebrow">Why teams choose us</div>
                <h2>Security, visibility, and speed without friction.</h2>
              </div>
              <div className="section-copy">
                We combine real-time insight with policy enforcement so teams can move quickly while staying compliant and protected.
              </div>
            </div>

            <div className="testimonials">
              {testimonials.map((item) => (
                <article key={item.author} className="quote-card">
                  <div className="quote-mark">“</div>
                  <p>{item.quote}</p>
                  <div className="author">
                    <div style={{ display: "flex", alignItems: "center", gap: 12 }}>
                      <div className="avatar">{item.author.charAt(0)}</div>
                      <div>
                        <div className="author-name">{item.author}</div>
                        <div className="author-role">{item.role}</div>
                      </div>
                    </div>
                  </div>
                </article>
              ))}
            </div>
          </div>
        </section>

        <section id="pricing" className="section">
          <div className="container">
            <div className="section-head">
              <div>
                <div className="eyebrow">Simple pricing</div>
                <h2>Choose the level that fits your operating model.</h2>
              </div>
              <div className="section-copy">
                Transparent plans designed for startups, scaling organizations, and enterprise teams managing sensitive systems.
              </div>
            </div>

            <div className="pricing-grid">
              {plans.map((plan) => (
                <div key={plan.name} className={`plan-card ${plan.featured ? "featured" : ""}`}>
                  {plan.featured && <span className="popular">Popular</span>}
                  <div className="plan-name">{plan.name}</div>
                  <div className="price">
                    <strong>{plan.price}</strong>
                    {plan.price !== "Custom" && <span>/month</span>}
                  </div>

                  <div className="plan-description">{plan.description}</div>

                  <ul className="plan-features">
                    {plan.features.map((feature) => (
                      <li key={feature}>{feature}</li>
                    ))}
                  </ul>

                  <a href="#start" className={`btn ${plan.featured ? "btn-primary" : "btn-secondary"}`}>
                    {plan.featured ? "Get started" : "Choose plan"}
                  </a>
                </div>
              ))}
            </div>

            <div className="cta-banner" id="start">
              <div>
                <h3>Turn operational complexity into clarity.</h3>
                <p>Launch your next-generation system strategy with Technologic.</p>
              </div>

              <div className="cta-row" style={{ marginTop: 0 }}>
                <a href="#" className="btn btn-primary">Book a consultation</a>
                <a href="#" className="btn btn-secondary">Talk to sales</a>
              </div>
            </div>
          </div>
        </section>
      </main>

      <footer className="footer">
        <div className="container footer-shell">
          <div className="brand">
            <div className="brand-mark">T</div>
            <span>Technologic</span>
          </div>

          <div className="footer-links">
            <a href="#platform">Platform</a>
            <a href="#solutions">Solutions</a>
            <a href="#security">Security</a>
            <a href="#pricing">Pricing</a>
          </div>

          <div>© 2026 Technologic. All rights reserved.</div>
        </div>
      </footer>
    </div>
  );
}