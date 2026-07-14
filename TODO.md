# TODO - Project Tasks

## Completed Tasks:

### Group Chat UI Enhancements:

- [x] Enhanced group chat message UI - sender profile image and name above message bubbles
- [x] Added slide-up panel with sender contact information when clicking group messages
- [x] Added "Add to Contacts" button if sender not in contacts
- [x] Added "Message" button if sender already in contacts

### Stories Page Enhancements:

- [x] Enhanced stories page with improved styling and animations

### Settings Page Enhancements:

- [x] Enhanced settings page with more features and options
- [x] Added Account settings (Edit Profile, Change Password, Active Sessions, Download Data)
- [x] Added Privacy settings (Last Seen, Profile Photo, Read Receipts, Group Settings, Blocked Contacts)
- [x] Added Notifications settings (Push, Sound, Vibration, Message Preview)
- [x] Added Storage & Data settings
- [x] Added App settings (Theme, Language, App Notifications)
- [x] Added Help & Support section

### Contacts Page Enhancements:

- [x] Enhanced contacts page with more features and options
- [x] Added favorites section with quick access
- [x] Added contact info slide-up panel with details
- [x] Added quick action buttons (Message, Call, Video)
- [x] Added view profile, favorite, share, delete actions
- [x] Improved create group modal with better UI
- [x] Added incoming call popup with video call support
- [x] Improved search functionality

### Add Friend System:

- [x] Created friends.html page for managing friend requests with tabs:
  - Requests tab: Shows received friend requests with Accept/Reject buttons
  - Sent tab: Shows sent requests with Cancel option
  - Friends tab: Shows accepted friends list
- [x] Added CSS/friends.css with modern UI styling
- [x] Added Friends navigation link to all main pages
- [x] Friend request functionality:
  - Send friend requests by mobile number
  - Accept/Reject incoming requests
  - Cancel sent requests
- [x] Real-time updates using Firestore onSnapshot listeners
- [x] Added "Friends" privacy option to stories (Friends Only)
- [x] Friends become contacts when request is accepted

## Pending Tasks:

### Chatting.html Advanced Features (requested)

- [ ] Implement pagination/scoped message loading (performance)
- [ ] Implement per-chat drafts persistence (localStorage)
- [ ] Improve delivery/seen status modeling & UI (sent/delivered/seen)
- [ ] Implement reply (quote) feature in context menu + rendering
- [ ] Add media upload progress + cancel (images + documents + voice)
- [ ] Add undo delete + soft-delete behavior (optional if too heavy)
