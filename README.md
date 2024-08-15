# WebView2 bug demo

Minimal repro for https://github.com/MicrosoftEdge/WebView2Feedback/issues/4743

- Build fails with error MC3074:
>The tag 'WebView2' does not exist in XML namespace 'clr-namespace:Microsoft.Web.WebView2.Wpf;assembly=Microsoft.Web.WebView2.Wpf'. Line 13 Position 10.
- Switch WebView2 NuGet in `ControlsLibrary.csproj` to version `1.0.2592.51` and see that build succeeds.
