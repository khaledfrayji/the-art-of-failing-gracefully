# 💥 error.tsx — Segment Error Boundary

## 📌 What It Is

A special file that catches **runtime errors in a route segment**.

---

## 🧠 How It Works

* Acts like a React Error Boundary
* Wraps the route automatically
* Prevents the whole app from crashing

👉 Errors bubble up to the nearest `error.tsx` ([Next.js][1])

---

## 📍 Scope

Only affects:

* Its route segment
* Its children

---

## ⚠️ Important Rule

It does NOT catch:

* Errors in the same `layout.tsx`

---

## 🧠 Mental Model

> “Local containment of failure”

---

## 🎤 Teaching Line

> error.tsx is where failure becomes **recoverable UI**


