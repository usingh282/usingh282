## Hi there 👋

Project Description: Flutter Picture-in-Picture (PIP) Video Calling App with Agora SDK

Overview:
This Flutter application demonstrates how to integrate video calling capabilities using the Agora RTC (Real-Time Communication) Engine SDK. The app allows users to join a video call channel, view local and remote video feeds, and toggle speakerphone functionality. The primary feature of this project is the implementation of Picture-in-Picture (PIP) mode, enabling users to multitask while participating in a video call.

Key Features:

Agora RTC Engine Integration:

Utilizes the Agora RTC Engine SDK for establishing real-time video communication.
Implements features such as joining channels, enabling video, and configuring video encoder settings.
Picture-in-Picture (PIP) Mode:

Displays the local video feed (using VideoPlayer) and remote video feed (via RtcRemoteView.SurfaceView) simultaneously on the screen.
The local video feed is shown in a dedicated area, allowing users to resize and position it while interacting with other applications.
User Interface:

Provides a simple and intuitive UI with a text field for entering the channel name and a button to initiate the video call.
Includes a floating action button for toggling the speakerphone during the call.
Video Playback:

Integrates VideoPlayer for playing local video assets (assets/local_video.mp4) during the call initiation phase.
Ensures seamless initialization and disposal of the video player resources (VideoPlayerController).
Error Handling and State Management:

Implements error handling for Agora API calls and asynchronous operations to maintain application stability.
Manages application state using Flutter's StatefulWidget to update UI components based on real-time events (e.g., user joining or leaving the channel).
Usage Scenario:

User Interaction: Users launch the app, enter a channel name to join a video call session, and are presented with a split-screen view of their own video feed and the remote participant's feed.
Multitasking: Users can continue using other apps or multitask on their device while keeping the video call active in a resizable PIP window.
Implementation Details:

Dependencies: Utilizes agora_rtc_engine for real-time communication and video_player for local video playback within the Flutter framework.
Assets: Requires assets/local_video.mp4 to be included in the project for demonstrating local video playback during call initiation.
Future Enhancements:

Enhanced UI/UX: Implement additional UI enhancements such as user avatars, chat functionality, and screen sharing capabilities.
Performance Optimization: Optimize video streaming quality and bandwidth utilization for improved user experience on different network conditions.
Conclusion:
This project serves as a practical example of integrating real-time video communication capabilities using Agora SDK in a Flutter application, highlighting the versatility of Flutter for building cross-platform multimedia applications with advanced features like Picture-in-Picture mode.

