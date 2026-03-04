# CASE — Component Guide

## Buttons

### Primary CTA
```html
<button class="btn-primary">Create Your CASE</button>
```
```css
.btn-primary {
  background: #3B82F6;
  color: #F1F5F9;
  padding: 14px 28px;
  border-radius: 8px;
  font-weight: 600;
  font-size: 16px;
  border: none;
  cursor: pointer;
  transition: transform 0.2s, box-shadow 0.2s;
}
.btn-primary:hover {
  transform: scale(1.02);
  box-shadow: 0 0 20px rgba(59, 130, 246, 0.5);
}
```

### Secondary CTA
```css
.btn-secondary {
  background: transparent;
  color: #F1F5F9;
  padding: 13px 27px;
  border-radius: 8px;
  border: 1px solid rgba(255, 255, 255, 0.2);
  font-weight: 500;
  font-size: 16px;
  transition: border-color 0.2s, color 0.2s;
}
.btn-secondary:hover {
  border-color: #3B82F6;
  color: #3B82F6;
}
```

### Gradient CTA (Final section)
```css
.btn-gradient {
  background: linear-gradient(135deg, #3B82F6, #8B5CF6);
  color: white;
  padding: 18px 40px;
  border-radius: 8px;
  font-weight: 700;
  font-size: 18px;
  box-shadow: 0 0 40px rgba(59, 130, 246, 0.3);
  transition: transform 0.2s, box-shadow 0.2s;
}
.btn-gradient:hover {
  transform: scale(1.02);
  box-shadow: 0 0 60px rgba(59, 130, 246, 0.5);
}
```

---

## Feature Card

```html
<div class="feature-card">
  <div class="feature-icon">⚡</div>
  <h3>Instant Deployment</h3>
  <p>Deploy your portfolio in seconds with a single click. No complex configurations needed.</p>
</div>
```
```css
.feature-card {
  background: #1E293B;
  border: 1px solid rgba(255, 255, 255, 0.08);
  border-radius: 16px;
  padding: 28px;
  transition: transform 0.3s ease, border-color 0.3s ease, box-shadow 0.3s ease;
}
.feature-card:hover {
  transform: translateY(-4px);
  border-color: rgba(59, 130, 246, 0.4);
  box-shadow: 0 8px 40px rgba(59, 130, 246, 0.15);
}
```

---

## Step Card (How It Works)

```css
.step-card {
  background: #1E293B;
  border: 1px solid rgba(255, 255, 255, 0.08);
  border-radius: 16px;
  padding: 32px 24px;
  text-align: center;
}

/* Highlighted middle step */
.step-card.highlight {
  border-color: rgba(59, 130, 246, 0.6);
  box-shadow: 0 0 40px rgba(59, 130, 246, 0.2);
  transform: translateY(-8px);
}
```

---

## Glassmorphism Panel

```css
.glass-panel {
  background: rgba(30, 41, 59, 0.6);
  backdrop-filter: blur(12px);
  -webkit-backdrop-filter: blur(12px);
  border: 1px solid rgba(255, 255, 255, 0.1);
  border-radius: 16px;
  box-shadow: 0 20px 60px rgba(0, 0, 0, 0.4);
}
```

---

## Trust Badge Row

```html
<div class="trust-row">
  <span>✔ No credit card</span>
  <span>✔ Deploy in seconds</span>
  <span>✔ Free forever</span>
</div>
```
```css
.trust-row {
  display: flex;
  gap: 24px;
  font-size: 14px;
  color: #94A3B8;
  font-weight: 500;
}
.trust-row span { color: #94A3B8; }
.trust-row span::first-letter { color: #3B82F6; }
```

---

## Section Label

```css
.section-label {
  font-size: 13px;
  font-weight: 600;
  letter-spacing: 0.15em;
  text-transform: uppercase;
  color: #3B82F6;
  margin-bottom: 12px;
}
```

---

## Accent Headline (colored word)

```html
<h2>Everything You Need to <span class="accent">Shine</span></h2>
```
```css
.accent {
  color: #3B82F6;
}
```
