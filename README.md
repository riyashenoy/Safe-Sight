# SafeSight | Reality Hack 2026

AR-powered personal safety for college campuses built on Snap Spectacles. SafeSight creates a shared, real-time safety network that keeps you present and aware without requiring you to look at your phone.

---

## Features

- **AR Navigation** - Follow a heads-up arrow along a Google Maps walking route to your destination
- **Hazard Flagging** - Report suspicious individuals, environmental hazards, or armed individuals via palm-anchored buttons
- **Real-Time Alerts** - Instantly notify and receive alerts from nearby users within a 1-mile radius
- **Dynamic Re-routing** - Automatically receive safer walking routes around reported hazards
- **Blue Light Locator** - See the nearest campus emergency blue light stations in AR
- **Emergency Mode** - Records 5 seconds of POV footage and sends it with your location to trusted contacts via a companion iOS app

---

## Built With

- [Lens Studio](https://ar.snap.com/lens-studio) - AR lens development for Snap Spectacles
- [Snap Cloud](https://developers.snap.com/spectacles/about-spectacles-features/snap-cloud-storage) - Real-time hazard sharing and emergency video upload
- [Google Maps Routes API](https://developers.google.com/maps/documentation/routes) - Walking route generation and hazard-aware re-routing
- [Supabase](https://supabase.com) - Backend database for hazard and location data
- Swift - iOS companion app
- TypeScript - Lens scripting

---

## Challenges

- Integrating the Google Maps Routes API to efficiently parse waypoints and trigger re-routing around dynamic hazard locations
- Managing lat/lon coordinate syncing for live hazard updates with low latency
- Building a reliable frame capture, encode, and upload pipeline for emergency video
- Wiring Supabase and Snap Cloud together for video stitching in the companion app

---

## Roadmap

- [ ] `.edu` email verification for campus-locked access
- [ ] Expanded routing intelligence using spatial data and historical hazard patterns
- [ ] AI audio assistant for real-time situational guidance
- [ ] Alert validation and misuse filtering
- [ ] Integration with official campus safety systems
- [ ] User testing to refine interaction speed and clarity

---

## License

MIT
