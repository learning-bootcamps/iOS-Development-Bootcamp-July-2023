# Weather App

## Project Description

Develop an iOS weather application that interacts with the OpenWeatherMap API to retrieve and display weather information for a specific city. The app will provide users with up-to-date weather details, including temperature, humidity, wind speed, and weather conditions.

## Rules & Guidelines

1. Use SwiftUI for UI development.
1. Implement data persistence, in-device store only.
1. Ensure the app is responsive and works on different iOS devices.
1. Follow [Human Interface Guidelines (HIG)](https://developer.apple.com/design/human-interface-guidelines/) for consistent design.
1. Test thoroughly for bugs and errors.
1. Properly structured and documented code.
1. Submit the project by the specified deadline.

## Key Features

1. **City Selection:** Users should be able to input a city name to view its weather information.
2. **Weather Display:** Display current weather details, such as temperature, humidity, wind speed, and weather conditions.
3. **Icon Representation:** Utilize appropriate weather icons to visually represent the weather conditions.
4. **Search Functionality:** Implement a search feature to enable users to easily find and select their desired city.
5. **Error Handling:** Provide appropriate error messages and notifications for cases where the city data cannot be retrieved or the API request fails.
6. **Units Conversion:** Include an option to switch between metric and imperial units for temperature and other measurements.
7. **Caching:** Implement a simple caching mechanism to store previously fetched weather data for faster access when revisiting the same city.

## Technical Requirements

1. **API Integration:** Utilize the OpenWeatherMap API (https://openweathermap.org/api) to retrieve weather data based on the city name.
2. **Networking:** Use a networking library (e.g., Alamofire or URLSession) to make API requests and handle responses.
3. **Data Parsing:** Parse the JSON data from the API response to extract relevant weather details.
4. **User Interface:** Design an intuitive and user-friendly interface using UIKit or SwiftUI, including appropriate labels, icons, and layout.
5. **Icon Integration:** Incorporate weather icons in the UI to visually represent weather conditions. Consider using FontAwesome icons or similar resources.
6. **Search Implementation:** Implement a search bar or search field for users to input city names.
7. **Unit Selection:** Create a settings section to allow users to choose between metric and imperial units for temperature and other measurements.
8. **Error Handling:** Implement error handling for cases such as network errors, invalid city names, and API errors. Display relevant messages to the user.
9. **Caching Mechanism:** Develop a basic caching mechanism using UserDefaults or a similar approach to store and retrieve previously fetched weather data.
10. **App Icon and Launch Screen:** Design an app icon and launch screen that align with the weather theme and branding.

## Ideas for Extra Credit

1. **Location Services:** Incorporate the user's device location to automatically fetch weather data for their current location.
2. **Extended Forecast:** Provide a forecast for the upcoming days in addition to the current weather.
3. **Detailed Weather Conditions:** Offer additional weather details, such as sunrise/sunset times and atmospheric pressure.
4. **Themes:** Implement different visual themes or color schemes for the app's interface.
5. **Animated Icons:** Add animations to weather icons to reflect real-time weather changes.

## Inspiration

- For better inspiration and user-experience checkout the Apple Weather App
- You may mimic real world app designs using [Mobbin](https://mobbin.com/browse/ios/screens?sort=popularity) or [Dribbble](https://dribbble.com).

## Submission Guidelines

- Create new repository name it as "iOS-Developemnt-Bootcamp-July-2023-Project-2".
- Upload your project files to the repo you just created.
- Submit your project repo link as comment to [here](https://github.com/learning-bootcamps/iOS-Development-Bootcamp-July-2023/issues/22).

## Grading Criteria

Your project will be graded based on the following criteria:

- Correctness and completion of tasks (50%)
- Code quality, readability, and adherence to best practices (30%)
- Creativity and utilization of SwiftUI features (20%)

## Additional Notes

- Avoid plagiarism; write the code by yourself.
- Late submissions will not be accepted without prior approval.

## Deadline

Submit your project prior start of next session.
