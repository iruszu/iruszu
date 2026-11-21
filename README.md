# Hi, I'm Kellie 👋

iOS engineer and Business + Computer Science student at **UBC** in Vancouver. I build native Apple-platform apps, and I care most about the ones that make technology work for people it usually leaves out.

- 🍎 Previously **iOS Engineering Intern at Apple** on the Sports app team (New York)
- 🎓 B.Com in Business & Computer Science, Data Science minor at UBC (expected Dec 2027)
- ♿ Long-standing interest in **accessibility**: building for underserved users is why I started coding
- 🌱 Currently learning: mobile system design and distributed systems
- 📫 Reach me: kellieh.exe@gmail.com

---

## 🛠️ Tech I work with

**Languages:** Swift · C++ · Python · TypeScript · Java · SQL
**Apple:** SwiftUI · UIKit · Combine · Swift Concurrency · CoreLocation · HealthKit · MapKit · ActivityKit · WidgetKit · AVFoundation · XCTest
**Other:** React · Git · REST APIs · Figma

---

## 📱 Featured projects

### 🏃‍♀️ [Runify](https://github.com/YOUR-USERNAME/runify)
A real-time GPS run tracker for iOS with background location, HealthKit sync, and Live Activities.
- **Location pipeline:** `CLLocationManager` with background location updates, filtering on `horizontalAccuracy` and speed to drop GPS noise before computing distance and rolling pace
- **Route rendering:** live polyline drawn with `MKPolyline` / `MKOverlayRenderer`, plus split-by-kilometre pace breakdowns
- **HealthKit integration:** writes workouts with `HKWorkoutBuilder` and attaches the route as an `HKWorkoutRoute`, so runs appear natively in Apple Fitness and Health
- **Live Activities:** `ActivityKit` + WidgetKit extension shows elapsed time, distance and pace on the Lock Screen and Dynamic Island, updated from the app process during the run
- **Architecture:** MVVM with Swift Concurrency (`async/await`, `@MainActor`) and protocol-based services so location and HealthKit can be mocked in XCTest

`Swift` `SwiftUI` `CoreLocation` `MapKit` `HealthKit` `ActivityKit` `WidgetKit` `XCTest`

### 🗣️ [LOQUI](https://github.com/YOUR-USERNAME/loqui)
An assistive communication (AAC) app that helps seniors with speech impairments communicate independently.
- **Text-to-speech:** `AVSpeechSynthesizer` with adjustable voice, rate and pitch so users can tune output to their hearing and preference
- **Accessibility-first UI:** full **VoiceOver** support, **Dynamic Type**, high-contrast colour, and large hit targets designed around reduced motor control
- **Phrase boards:** customisable categories of common phrases with on-device persistence, so the app works fully offline
- **User research:** designed iteratively with feedback from seniors to reduce taps-to-speech for everyday requests

`Swift` `AVFoundation` `VoiceOver` `Dynamic Type` `Accessibility`

### 🎟️ Prosper Portal
A full-stack event management platform for Prosper Foundation, built by a small team I lead.
- **Role-based access control (RBAC):** separate permission scopes for admins, organisers and attendees, enforced server-side
- **Jotform integration:** ingests registration submissions through the Jotform API / webhooks and maps them into structured attendee records
- **Event lifecycle:** event creation, registration, capacity tracking and attendee management through a REST API
- **Team leadership:** own sprint planning, code review and task breakdown for a 4-person dev team

`TypeScript` `React` `REST API` `RBAC` `Webhooks` `Team Lead`

### 🔴 [Pokédex](https://github.com/YOUR-USERNAME/pokedex) *(in progress)*
A SwiftUI Pokédex backed by the PokéAPI, built as a playground for production-style networking and architecture.
- **Networking layer:** generic, protocol-oriented API client using `URLSession` + `async/await` and `Codable` decoding
- **Pagination & performance:** infinite scroll with offset-based pagination, prefetching, and an `NSCache` image cache to avoid redundant downloads
- **Concurrency:** parallel detail fetches with `TaskGroup`, cancellation on scroll-away, and structured error handling
- **Testing:** dependency injection so the API client can be swapped for a mock in unit tests

`Swift` `SwiftUI` `URLSession` `async/await` `Codable` `NSCache`

---
