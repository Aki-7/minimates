# MiniMates

**Overview**  
MiniMates is an HCI research project exploring remote meetings in Augmented Reality (AR) using 3D miniature avatars. This repository provides the core avatar formation and redirection algorithms used in our system. For an in-depth discussion of the research and findings, please refer to our paper ([link placeholder]).

---

## Purpose of This Repository

To actually run the system, you would need to set up the Meta Avatar SDK, Photon, and a suitable network environment—each of which involves multiple complex steps that are beyond the scope of this repository. Instead, **the main purpose here is to share the implementations of our avatar formation and redirection algorithms**.

---

## Repository Contents

- **`minimates.unitypackage`**  
  Contains all relevant scripts and assets. Import this package into Unity to view or study the MiniMates codebase.

---

## Project Structure

MiniMates is composed of two main components: the server side (central control) and the client side (installed on Meta Quest 3).

- **Server Side**  
  `CMU/APL/MiniMates/Sources/Server/`  
  Handles core logic such as avatar formation and redirection.

- **Client Side**  
  `CMU/APL/MiniMates/Sources/Client/`  
  Receives commands from the server and updates avatar positions/orientations accordingly.

---

## Abstract (for Reference)

> Remote meetings using 3D avatars in Augmented Reality (AR) allow effective communication and enable users to retain awareness of their surroundings. However, positioning 3D avatars effectively and consistently for all users in AR is challenging since most spaces, such as offices or living rooms, are not large enough to accommodate multiple life-sized avatars without interference. To address this issue, we contribute MiniMates—a novel approach leveraging miniature avatars, which make it possible to place multiple remote users in a limited physical space. We see MiniMates as complementary to traditional 2D video conferencing and immersive telepresence. Our approach automatically adjusts the formation of avatars and redirects users' head and body orientation to facilitate communication. Results from our user study (n = 24) show that participants experience a higher sense of co-presence compared to video conferencing, and can utilize MiniMates to communicate the direction of their interactions non-verbally and manage multiple simultaneous conversations.

For the full research details, please refer to our paper ([link placeholder]).

---

## Contact

For questions or inquiries regarding MiniMates, feel free to email:  
**akihirorz@gmail.com**
