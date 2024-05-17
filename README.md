# VWO Insights SDK for iOS

VWO Insights helps you analyze user behavior in your application based on interactions such as application launch, taps, scrolls, and flings. By attributing these actions to critical business events like purchases and sign-ups (which are considered conversions), VWO Insights enables you to identify why users might not be converting. This tool is essential in the research stage of experience optimization, providing insights into what users are (or are not) doing in your application and helping to determine why.

Understanding user behavior through VWO Insights is the foundation of an effective optimization program, guiding you towards data-backed ideation and testing without relying on assumptions.

## Features

- **User Behavior Analysis:** Track and analyze critical user actions within the application.
- **Conversion Tracking:** Associate user actions with custom events to measure effectiveness.
- **Optimization Insights:** Gain insights into potential problem areas affecting user conversion.
- **Data-backed Decisions:** Make informed decisions to enhance the user experience based on actual user data.

## Installation

For detailed installation instructions, visit our [Installation Guide](https://developers.vwo.com/reference/mobile-insights-ios-installation).

## Quick Start

To integrate VWO Insights into your iOS application, follow these steps after completing the installation:

1. **Initialize VWO SDK**
   - Import VWO SDK into your application.
   - Initialize the SDK with your API key.

   ```swift
   import vwo_insights_ios_reactnative_sdk
   VWO.configure(accountId: "", sdkKey: "", userId: "")
   ```
   
2. **Track User Actions**
   - Implement tracking for various user actions throughout your application by start session recording.

   ```swift
   VWO.startSessionRecording()
   ```
3. **Analyze and Optimize**
   - Use the VWO dashboard to analyze tracked data and derive actionable insights.
   
   
For more detailed usage instructions, please refer to our [Developer Documentation](https://developers.vwo.com/reference/mobile-insights-introduction).

## Support
For any support queries or technical assistance, please contact our support team at [support@vwo.com](mailto:support@vwo.com)

## License
VWO Insights SDK is licensed under the Apache-2.0 License. See the [LICENSE](https://github.com/wingify/vwo-insights-ios-react-native-sdk/blob/main/LICENSE) file for more details.

