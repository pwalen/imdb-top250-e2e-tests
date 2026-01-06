# IMDb Top 250 – UI E2E Tests

This repository contains an educational end-to-end (E2E) UI test project
implemented using TypeScript and Puppeteer.

The goal of the project is to practice real-world browser automation,
test design, and decision-making typical for an SDET role.

---

## 🎯 Project Purpose

This project is focused on:
- practical UI test automation,
- working with a real, publicly available website,
- learning through hands-on implementation rather than tutorials,
- building a test suite incrementally, as in a professional environment.

It is **not a course**, **not a framework template**, and **not a scraping tool**.

---

## 🧪 Scope of Testing

The tests target:
- publicly accessible pages,
- functionality that does **not** require user authentication,
- UI behavior observable by any regular user.

The project intentionally avoids:
- API testing,
- backend integration,
- data persistence beyond test runtime.

---

## ⚠️ Legal & Ethical Notice

This project is created **for educational purposes only**.

- The tests interact with publicly available web pages using automated browsers.
- No data is scraped, stored, or redistributed.
- No proprietary source code, assets, or internal APIs are copied.
- The project does not bypass authentication, paywalls, or security mechanisms.

All website content remains the property of its respective owners.

---

## 🧱 Project Philosophy

- Tests are written incrementally and may evolve over time.
- Initial implementations may be simple or technical by design.
- Abstractions (such as Page Object Models) are introduced only when justified
  by real duplication or maintenance pain.
- The focus is on understanding UI behavior, timing, and stability,
  not on premature architecture.

---

## 🛠️ Technology Stack

- TypeScript
- Puppeteer
- Jest

---

## ▶️ Running the Tests

Install dependencies:

```
npm install
```

Run the test suite:

```
npm test
```

---

## 📌 Notes

- This repository is public by design and safe to share.
- It reflects a realistic learning and experimentation process.
- Code quality and structure may change as the project evolves.

---

## 📄 License

This project is licensed under the MIT License.
