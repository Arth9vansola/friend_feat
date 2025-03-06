# Feature Specification: Friend or Stranger

## Overview
This feature allows users to easily identify whether another user is a **Friend** or a **Stranger** within the platform. It simplifies the user experience by providing clear visual and functional distinctions between these two states of connection.

---

## Key Functionalities

### 1. Friend
- **Definition**: A user that you are connected with (mutual acceptance of a friend request).
- **Features**:
  - View full profile details (based on privacy settings).
  - Send direct messages.
  - See posts and activities shared with friends.
  - Interact with content (like, comment, share, etc.).
  - Receive activity updates in the news feed.

### 2. Stranger
- **Definition**: A user that you are not connected with.
- **Features**:
  - Limited profile visibility (based on public information).
  - Option to send a friend request.
  - Cannot send direct messages unless allowed by privacy settings.
  - Posts and activities remain hidden unless shared publicly.

---

## User Interface
- **Friend**:
  - Displayed with a "Friend" badge/icon next to the profile name.
  - Action buttons: 
    - ✅ **Message** 
    - ✅ **Unfriend** 

- **Stranger**:
  - Displayed with a "Stranger" badge/icon or no badge.
  - Action buttons:
    - ✅ **Add Friend** 
    - 🚫 **Message** (unless permitted by privacy settings).

---

## Privacy Settings
- Users can customize visibility and interaction levels for:
  - **Friends** (e.g., who can see posts, photos, or online status).
  - **Strangers** (e.g., restrict profile visibility, disable friend requests).

---

## Example Scenarios
1. **User A** views **User B's** profile:
   - If they are **Friends**, User A sees:
     - Full profile details, shared posts, and the option to message.
   - If they are **Strangers**, User A sees:
     - Limited public details and an option to send a friend request.

2. **Privacy Settings for Strangers**:
   - A user can set profile visibility so that only their name, profile picture, and mutual friends (if any) are visible.

---

## Future Enhancements
- Add a **"Close Friends"** tag for stronger connections.
- Introduce a **"Follower"** state for one-way connections.
- Allow users to send a limited number of temporary messages to strangers (subject to consent).

---

## Visual Mockup (Optional)
Use simple icons or colors to represent "Friend" and "Stranger":
- **Friend**: Green icon with a handshake.
- **Stranger**: Gray icon with a question mark.

---

## Conclusion

The Friend or Stranger feature enhances user experience by simplifying connection statuses and ensuring privacy controls. It provides clarity and consistency while fostering secure interactions on the platform.

