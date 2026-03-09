# iMessage Setup (OpenClaw)

- **Xcode 26.3** installed ✅
- **imsg** install blocked by Xcode license agreement.
- **Next step**:
  ```bash
  sudo xcodebuild -license accept
  brew install steipete/tap/imsg
  ```
- **Note**: Zscaler blocks Telegram/WhatsApp/Discord → iMessage is the only viable channel for public-facing bot communication.
