# 🌙 Noctaliæ (WIP)

**Scientific Dream Analysis App**

> *Analyze your dreams with science, not mysticism.*
> 

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://noctaliae-web.vercel.app)

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

**Live Demo:** https://noctaliae-web.vercel.app

> ⚠️ **Note:** The backend (Replit) goes to sleep after 1h of inactivity. If the demo doesn't work, the backend needs to be woken up first. Migration to Infomaniak (always-on hosting) is planned.
> 

---

## 📖 What is Noctaliæ?

Noctaliæ is a **scientific dream analysis application** based on sleep neuroscience research. Built on the work of **Isabelle Arnulf** (Pitié-Salpêtrière Hospital), **Allan Hobson**, **G. William Domhoff**, **Antti Revonsuo**, **Matthew Walker**, and **Erik Hoel**, it uses **6 validated analysis frameworks** to provide rigorous yet empathetic insights into your dreams.

### 🔬 Scientific Approach

- ✅ **No universal symbolism** – We reject esoteric interpretations
- ✅ **Evidence-based analysis** – Grounded in peer-reviewed neuroscience
- ✅ **Continuity hypothesis** – 65-90% of dream content links to waking life
- ✅ **Emotional regulation** – Dreams process emotions in a safe context
- ✅ **Threat simulation** – 82% of dreams are negative (adaptive function)

---

## ✨ Features

### 🆓 Free Version

- 🤖 **Unlimited analyses** with Llama 3.3 70B (Groq API)
- 🎙️ **Voice recording** with automatic transcription (Groq Whisper)
- 💬 **Text conversation** to explore your dreams deeper
- 📚 **30-day history** with local storage
- 🌍 **Multilingual** with auto-detection

### ⭐ Premium Version ($2.99/month)

- 🧠 **Claude Sonnet 4.5** analysis (higher quality)
- 💬 **Unlimited text conversations**
- 🎙️ **Voice assistant** for hands-free exploration
- 📊 **Advanced statistics** and patterns
- 📄 **PDF export** of analyses
- ♾️ **Unlimited history**

### 💎 Lifetime Version ($19.99 one-time)

- 🔓 All Premium features forever
- 🚀 Early access to new features
- 💜 Support the project long-term

---

## 🚀 How to Use

### Mobile App (Coming Soon)

1. **Record your dream** – Voice or text input upon waking
2. **Get instant analysis** – Scientific interpretation in seconds
3. **Explore deeper** – Ask follow-up questions via text or voice
4. **Track patterns** – See recurring themes and emotions over time

### Web Version (Live Now)

Visit [noctaliae-web.vercel.app](http://noctaliae-web.vercel.app) and:

1. Type or paste your dream
2. Click "Analyze"
3. Receive your scientific interpretation
> ⚠️ **Note:** The backend (Replit) goes to sleep after 1h of inactivity. If the demo doesn't work, the backend needs to be woken up first. Migration to Infomaniak (always-on hosting) is planned.
> 


---

## 🧠 The 6 Analysis Frameworks

| Dream Type | Framework | Researcher |
| --- | --- | --- |
| Bizarre/surreal | Activation-Synthesis | Allan Hobson |
| Recent event-related | Continuity Hypothesis | G. William Domhoff |
| Emotionally charged | Emotional Regulation | Isabelle Arnulf / Perrine Ruby |
| Nightmare/threat | Threat Simulation Theory | Antti Revonsuo |
| Skill rehearsal | Memory Consolidation | Matthew Walker |
| Recurring | Continuity + Regulation | Multiple researchers |

---

## 🔬 Scientific Foundations

### The 10 Fundamental Principles (Isabelle Arnulf)

1. **Dreams are concrete cognitive activity** – Not symbolic mysteries
2. **Dreams occur in real-time** – No time compression
3. **Bidirectional communication is possible** – Via eye signals in lucid dreams
4. **REM is not complete disconnection** – Brain remains partially connected
5. **Threat simulation** – 82% of dreams are negative (adaptive function)
6. **Emotional regulation** – Processing emotions in a calm chemical context
7. **Continuity with waking life** – 65-90% content linked to past 24h
8. **Creativity and problem-solving** – Unusual associations
9. **Physical behavior reflects mental content** – Psycho-physiological correlations
10. **Everyone dreams, forgetting is normal** – Encoding issue, not absence

---

## 🛠️ Tech Stack

### Mobile App (React Native)

```
React Native + Expo SDK 54
├── expo-av (audio recording)
├── AsyncStorage (local storage)
├── React Navigation (screens)
└── axios (API calls)
```

### Backend (Node.js)

```
Node.js + Express
├── Groq API (Llama 3.3 70B) – FREE
├── Groq Whisper (transcription) – FREE
├── Claude API (Anthropic) – $0.01/analysis
└── OpenAI TTS (voice assistant) – $0.02/response
```

### Deployment

- **Web:** Vercel
- **Backend:** Replit → Infomaniak (migration in progress)
- **Mobile:** Expo EAS Build (iOS + Android)

---

## 📊 Architecture



---

## 🔐 Privacy & Security

### Current Implementation

- ✅ **No audio storage** – Audio is transcribed then immediately deleted
- ✅ **Local-first** – Dream history stored on device (AsyncStorage)
- ✅ **No tracking** – No analytics, no third-party cookies

### Planned (Before Store Launch)

- 🔒 **Firebase Authentication** (OAuth2 + PKCE)
- 📜 **GDPR-compliant Privacy Policy**
- 🗑️ **Right to erasure** (complete account deletion)
- 🔐 **E2EE encryption** if cloud storage added
- 📤 **Data portability** (export your data)

---

## 🗺️ Roadmap

### ✅ Phase 0 - Genesis (Oct 2025)

- ✅ Scientific research (Arnulf, Hobson, Domhoff, Revonsuo, Walker, Hoel)
- ✅ Prompt engineering with 6 analysis frameworks
- ✅ Web prototype validation
- ✅ Free version with Groq (Llama 3.3 70B)

### 🔄 Phase 1 - Mobile MVP (Nov 2025 - In Progress)

- ✅ React Native app structure
- ✅ Voice recording with Whisper transcription
- ✅ Dream analysis (Free + Premium toggle)
- ✅ Local history with playback
- 🔄 Text conversation (in progress)
- ⏳ Voice assistant (Premium)
- ⏳ Firebase Authentication
- ⏳ Infomaniak backend migration

### ⏳ Phase 2 - Monetization (Dec 2025)

- In-app purchases (iOS + Android)
- Premium subscription ($2.99/month)
- Lifetime purchase ($19.99 one-time)

### ⏳ Phase 3 - Advanced Features (2026)

- Multi-device sync (Firebase)
- PDF export
- Dream statistics & insights
- Wake-up reminders

---

## 💰 Cost Analysis

### Per Dream Analysis

| Version | STT | LLM | TTS | Total |
| --- | --- | --- | --- | --- |
| **Free** | $0 (Groq) | $0 (Groq) | N/A | **$0** |
| **Premium (text)** | $0 (Groq) | $0.01 (Claude) | N/A | **$0.01** |
| **Premium (voice)** | $0 (Groq) | $0.01 (Claude) | $0.02 (OpenAI) | **$0.03** |

### Monthly Budget Example (Premium User)

- 30 dream analyses: 30 × $0.01 = **$0.30**
- 10 voice conversations: 10 × $0.03 = **$0.30**
- **Total: ~$0.60/month** (on $2.99 subscription = **80% profit margin**)

---

## 🤝 Contributing

Contributions are welcome! Whether you're a developer, designer, neuroscience researcher, or simply passionate about dreams, there's a place for you.

### How to Contribute

1. **Fork** this repository
2. Create your branch: `git checkout -b feature/my-feature`
3. Commit your changes: `git commit -m 'Add X'`
4. Push: `git push origin feature/my-feature`
5. Open a **Pull Request**

### Areas of Contribution

- 💻 Code (frontend/backend)
- 🎨 Design & UX
- 🔬 Scientific validation
- 📝 Documentation
- 🌍 Translations
- 🐛 Bug reports

### Development Principles

1. **Science-first** – All features must be evidence-based
2. **Privacy-first** – User data is sacred
3. **Accessibility-first** – Design for everyone
4. **Open-source** – Transparent development

---

## 📄 License

This project is licensed under the **MIT License** – see the LICENSE file for details.

---

## 🙏 Acknowledgments

### Scientific Research

- **Isabelle Arnulf** – Pitié-Salpêtrière Hospital, Paris (sleep neuroscience)
- **Allan Hobson** – Activation-Synthesis Model
- **G. William Domhoff** – Continuity Hypothesis
- **Antti Revonsuo** – Threat Simulation Theory
- **Matthew Walker** – Memory Consolidation (UC Berkeley)
- **Erik Hoel** – Overfitted Brain Hypothesis (Tufts University)

### Technologies

- Anthropic Claude – AI analysis
- Groq – Free Llama 3.3 & Whisper
- OpenAI – Text-to-Speech

---

## 📞 Contact

- **Website:** [noctaliae-web.vercel.app](http://noctaliae-web.vercel.app)
- **Email:** [contact@thomasmaury.fr](mailto:contact@thomasmaury.fr)
- **LinkedIn:** [Thomas Maury – Creator of Noctaliæ]({{https://www.linkedin.com/in/thomasmaury/}})
- **GitHub:** [github.com/tm-ai0/noctaliae](http://github.com/tm-ai0/noctaliae)

---

## 📊 Project Status

**Current Focus:** Completing Phase 1 Mobile MVP + Firebase Auth + GDPR Compliance

---

### 🌙 *"The dream is not a coded message to decipher. It is a concrete cognitive activity."*

- **Isabelle Arnulf**

### 🌙 *"We can consider REM sleep as overnight therapy, a form of emotional first aid."*

- **Matthew Walker**, Why We Sleep

---

Made with 🧠 and ❤️ by [Thomas Maury]({{https://thomasmaury.fr}})

**⭐ If you like this project, give it a star on GitHub!**
