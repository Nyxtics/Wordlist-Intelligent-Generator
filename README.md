# 🧠 Wordlist Intelligent Generator

![License](https://img.shields.io/github/license/Nyxtics/Wordlist-Intelligent-Generator?style=flat-square)
![Stage](https://img.shields.io/badge/Project%20Stage-Open%20Beta-orange?style=flat-square)
![Sec](https://img.shields.io/badge/Focus-Infosec%20%2F%20Red%20Team-red?style=flat-square)

An intelligent, context-driven wordlist generator designed for penetration testing. It ranks, filters, and prioritizes combinations based on target profiles, avoiding combinatorial explosion.

> ⚠️ **Project Status:** This tool is currently under active development and continuous improvement.

---

## 🚀 Key Features

* **High-Relevance Funnel:** Prioritizes natural combinations (names, dates, close preferences) at the top of the list. Complex variations, leet speak, and special characters are introduced progressively, avoiding early file pollution.
* **Multidimensional Ranking Algorithm:** Converts subjective target details (hobbies, sports teams, regional habits) into technical weight, instantly boosting the priority of related strings.
* **Adaptive Generation Control:** Implements a computing "effort budget." It automatically truncates stagnant stages to prevent combinatorial explosion and focus resources on paths with the highest yield.
* **Source-Level Filtering & Deduplication:** Cleans data on the fly. Key duplicates, keyboard patterns, and length constraints are checked during generation—never after.
* **High-Performance Architecture:** The generation engine runs entirely isolated from the main interface thread, ensuring a fully responsive UI with accurate ETAs and safe, instantaneous cancellation.
* **Intelligent Merger Module:** Includes a built-in utility to merge and mix external wordlists analytics-first, keeping the highest-ranked duplicate positions.

---

## 🎯 Why This Project?

Traditional dictionary generators create millions of dead lines that security professionals have to filter out later. This engine applies intelligence at the source. The result is not just a larger wordlist, but a cleaner, contextualized, and probability-oriented dataset optimized for efficient assessments.

---

## 🛠️ Getting Started & Testing (Free Trial)

This project is currently in its open beta phase and **ready for immediate testing!** To ensure security professionals can evaluate the tool's efficiency, the engine includes a built-in **7-day free trial** upon first launch.

### 📥 How to Test
1. Clone or download the repository.
2. Run the executable or MSI installer to automatically activate your **7-day evaluation period**.
3. Explore the full capabilities of the context-driven engine on your assessments.

### 🔑 Renewal & Feedbacks
Once your trial period expires, or if you want to share your experience during the test:
* **Request License Renewal:** Contact me directly via the e-mail address provided inside the application.
* **Share Feedback:** Bug reports, feature suggestions, and performance reviews are highly appreciated. Feel free to open an **Issue** here on GitHub or use the in-app contact info.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
