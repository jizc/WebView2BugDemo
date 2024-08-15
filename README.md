# WebView2BugDemo

Minimal repro for https://github.com/MicrosoftEdge/WebView2Feedback/issues/4743

- Build fails with error MC3074.
- Switch WebView2 NuGet in `ControlsLibrary.csproj` to version `1.0.2592.51` and see that build succeeds.
