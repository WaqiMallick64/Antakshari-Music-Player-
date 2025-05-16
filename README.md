# 🎵 Antaakshari - Console-based Music Player (DSA Project)

Antaakshari is a C++ console-based music player designed as a Data Structures and Algorithms (DSA) project. It features intelligent playlist management, secure multi-user support, a stack-based song history, and customizable playback—all built using fundamental DSA concepts.

## 👥 Group Members
- Muhammad Waqi Mallick
- Muhammad Usman
- Taha Wala Qadr

---

## 📌 Features

- 🎶 View and play all songs
- 🕒 Song timeline using a stack (history of played songs)
- 📜 Create and manage queues (custom song order)
- 🔁 Replay and volume adjustments
- 🧠 Most played song tracking
- 🔍 Search songs by title or artist
- 📂 Playlist management (create, add/remove songs)
- 🎲 Random song suggestion
- 👤 Multi-user login with password encryption
- 📚 File handling for persistent user and song data

---

## 🧰 Data Structures Used

- Circular Doubly Linked List (for song list)
- Circular Linked List (for playlists)
- Stack (for history)
- Queue (for song queue)
- Arrays (miscellaneous support)

---

## 🧱 Classes Overview

- `Song` – Represents a track with metadata and doubly circular linked list navigation.
- `Queue` – Circular linked list queue for song order.
- `CircLL` – Handles core circular linked list operations.
- `Playlist` – Custom playlist handler.
- `PlayListManager` – Manages multiple playlists.
- `Stack` – Maintains song play history.
- `UserInfo` – Manages user data and encrypts credentials.

---

## ⚙️ Algorithms Used

- **Insertion Sort** – Sorts song lists (Time: O(n²))
- **Rabin-Karp** – Efficient substring search for song titles/artists (Worst: O(mn))
- **Shift Cipher** – Encrypts user passwords (Time: O(n))
- **Random Song Picker** – Suggests a song at random (Time: O(n))

---

## 🖥️ Installation and Setup

1. **Download all source files** and place them in a single folder.
2. Install **Dev C++ Red Edition v6.3**.
3. Open Dev C++ > go to **Tools → Compiler Options**.
4. Under **"Add the following commands when calling the linker"**, paste:

-static-libgcc -lgdi32 -lcomdlg32 -luuid -loleaut32 -lole32 -lwinmm


5. Compile and run the project.

### 🔐 Sample User Accounts

You can use the following demo accounts to test the application:
Username: bananaman Password: banana123
Username: usman357 Password: usman123


You can also create new accounts from within the program.

---

## 🪄 Future Enhancements

- GUI for better user experience
- Playback integration using a media library
- Improved dynamic memory management
- Secure user authentication with private/public playlists
- Friend system and playlist sharing

---

## 📄 License

This project is part of an academic course and is for educational purposes only.

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss your proposed changes.

---

## 📫 Contact

For questions or collaboration:
- Muhammad Waqi Mallick: [LinkedIn: https://www.linkedin.com/in/muhammad-waqi-mallick-4b7b912a3/]
- Muhammad Usman: [LinkedIn: https://www.linkedin.com/in/muhahmmad-usman-91973b2b0/]
- Muhammad Usman: [LinkedIn: https://www.linkedin.com/in/taha-walaqadr-9652672b8/]
