<!-- THE SHIELDS -->
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]

# Exploration of Navigation Component in Android
**Android Jetpack's Navigation component** is a suite of libraries, tooling and guidance for in-app navigation. The component centralizes all of the navigation information of your app in a navigation graph, providing a robust framework for implementing everything from simple button clicks to complex navigation UI patterns, such as app bars and the navigation drawer. The Navigation component also ensures a consistent and predictable user experience by adhering to an established set of [Navigation Principles](https://developer.android.com/guide/navigation/navigation-principles/).

The Navigation component consists of three key parts that are described below:

- **Navigation graph**: An XML resource that contains all navigation-related information in one centralized location. This includes all of the individual content areas within your app, called destinations, as well as the possible paths that a user can take through your app.

[![Navigation Graph][navigation-graph]][navigation-graph]

<p align="center"><i>Navigation Graph illustration</i></p>

- `NavHost`: An empty container that displays destinations from your navigation graph. The Navigation component contains a default NavHost implementation, [NavHostFragment](https://developer.android.com/reference/androidx/navigation/fragment/NavHostFragment/), that displays fragment destinations.
- `NavController`: An object that manages app navigation within a NavHost. The NavController orchestrates the swapping of destination content in the NavHost as users move throughout your app.

<br/>

## The Benefits
The Navigation component provides a number of other benefits, including the following:
- Handling fragment transactions.
- Handling Up and Back actions correctly by default.
- Providing standardized resources for animations and transitions.
- Implementing and handling deep linking.
- Including Navigation UI patterns, such as navigation drawers and bottom navigation, with minimal additional work.
- **Safe Args** - a Gradle plugin that provides type safety when navigating and passing data between destinations.
- `ViewModel` support - you can scope a ViewModel to a navigation graph to share UI-related data between the graph's destinations.

<br/>

You can use Android Studio's **Navigation Editor** to view and edit your navigation graphs.

[![Nav Editor][nav-editor]][nav-editor]

<p align="center"><i>Navigation Editor illustration</i></p>
<br/>

>For more documentation and resources related to the Navigation component, you can follow Android [Get started with the Navigation Component](https://developer.android.com/guide/navigation/navigation-getting-started/) to start navigating with Navigation Component.
>
>If you want to try the codelab from Android documentation, start building your [Navigation Codelab here](https://codelabs.developers.google.com/codelabs/android-navigation/index.html)!  

<br/>
<br/>

Thank you,  
*Samy Utomo* :smile: :thumbsup:


<!-- THE LINKS -->
[forks-shield]: https://img.shields.io/github/forks/samyutomo/android-navigation-component-explore?color=brightgreen&style=for-the-badge
[forks-url]: https://github.com/samyutomo/android-navigation-component-explore/network/members
[stars-shield]: https://img.shields.io/github/stars/samyutomo/android-navigation-component-explore?color=yellow&style=for-the-badge
[stars-url]: https://github.com/samyutomo/android-navigation-component-explore/stargazers
[navigation-graph]: misc/navigation-graph.png
[nav-editor]: misc/nav-editor.png
