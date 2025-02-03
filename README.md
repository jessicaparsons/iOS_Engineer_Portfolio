# iOS Engineer Portfolio
Showcasing my best Swift iOS apps that are crafted with clean code, great UI, and solid architecture.

# 1. **Royal Sea Journeys: Port Explorer**  

**Royal Sea Journeys: Port Explorer** is a fully-featured iOS application designed to bring the ultimate cruise itinerary to life. With a stunning user interface, Port Explorer harnesses the power of **MapKit** and external APIs to deliver dynamic travel content. Whether you're discovering unique shore excursions, exploring breathtaking ports of call, or planning your next adventure, this app is your ultimate digital companion for all things cruising.

## Screenshots
![AppStore Screenshots](assets/app_store_1.jpg)
![AppStore Screenshots](assets/app_store_2.jpg)

## Demo
| iPhone | iPad |
| ------------- | ------------- |
| ![App Demo](assets/app_demo.gif) | ![App Demo](assets/ipad_demo.gif) |

## **Key Features**

### 🗺 **Interactive Map Explorer**  
- Powered by **MapKit**, users can:
  - Navigate a world map to discover ports of call for various itineraries.  
  - Tap on interactive **map annotations** to explore detailed port information.
  - View real-time latitude and longitude coordinates via a sleek overlay.

### 📅 **API Provided Itinerary Highlights**  
- **Integrates with a travel API** to fetch itinerary and port data, and displays itineraries with carousel and grid layouts.
- Drill down into itinerary details with seamless navigation to ports of call.
- Utilizes the **Kingfisher** SKD for optimized image caching and loading.

### 📹 **Dynamic Video Galleries**  
- Integrates with the **Pixabay Video API** to showcase dynamically loaded travel videos

### 📷 **Customizable Photo Gallery**  
- A polished, user-friendly interface that supports dynamic filtering, lazy loading for performance, and toggleable grid views.
- Images are fetched from the external travel API and cached with Kingfisher, ensuring modularity and scalability.  
### 📱 **iPad Support**  
- The app fully supports **iPadOS**, offering a rich and immersive experience on larger screens.  

## **Other Highlights**  

- **Modern Swift Practices**  
  - Leveraged **async/await** for API calls and data fetching.
  - Used `@MainActor` annotations to ensure thread-safe UI updates.

- **UI and User Experience**  
 
  - Implemented **accessibility features** for improved usability, including VoiceOver support.  

- **Modular and Scalable Code**  

  - Used **MVVM** for scalable data flow management.


## 🚀 **Built With**  

- Swift 5
- SwiftUI
- Xcode 16.2 

### Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/RoyalSeaJourneys.git



# 2. ChildSafeRx
A trusted app for parents and caregivers, providing child-safe medication guidance and information.

## About
- Comprehensive list of child-safe medications.
- Detailed dosage, safety guidelines, and precautions.
- Simple, intuitive UI designed for caregivers.

## Screenshots
![AppStore Screen](assets/appstore_5.jpg)
|   |   |   |
| ------------- | ------------- | ------------- |
| ![Onboarding Screen](assets/onboarding_screen_1.png) | ![Onboarding Screen](assets/onboarding_screen_2.png) | ![Settings Screen](assets/settings_screen.png) |

## Demo
| iPhone | iPad |
| ------------- | ------------- |
| ![App Demo](assets/app_demo.gif) | ![App Demo](assets/ipad_app_demo.gif) |


## Key Features
- 📱 Modern iOS Development
  - Built using SwiftUI, leveraging declarative syntax for efficient and clean UI development.
  - Designed for iOS 18, ensuring compatibility with modern app design and functionality.
- 🖌️ Dynamic User Interface
  - Multi-screen onboarding flow implemented with PageTabView for a seamless user introduction.
  - Responsive and visually engaging child-friendly interface with dynamic, data-driven content.
- 📊 Advanced Data Management
  - Dynamically loads and organizes medication information using JSON parsing.
  - Custom data model processes JSON input efficiently.
  - Leveraged Swift's Codable protocol for clean and maintainable data decoding and handling.
- 🔒 State Management
  - AppStorage used for persistent data storage, enabling smooth state-saving functionality.
  - Dynamic views that adapt to user interaction and data changes.
- 📜 Dynamic Content Display
  - Designed dynamic List Views to render child-safe medications using reusable components.
  - Scalable and modular UI architecture for future feature expansion.
- 👨‍👩‍👧 User-Centric Design
  - Prioritized accessibility with child-friendly visuals and simple navigation.
  - Clear warnings and disclaimers to promote safe and responsible usage.
- 📂 Version Control and Documentation
  - Managed the project using Git for version control and GitHub for portfolio presentation.

## Built With
- Swift 5
- SwiftUI
- Xcode 16.2
