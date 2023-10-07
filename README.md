# Blazor Hybrid Web App sample

A sample project that shows how to share Razor components and pages between a .NET 8 Blazor Web app and a .NET MAUI hybrid app.

1. The Blazor Web App's pages and components were moved to the Razor Class Library project
1. The .NET MAUI Blazor Hybrid app's pages were deleted
1. The Blazor Web App and .NET MAUI Blazor Hybrid app now use the shared pages/components

Notes:

- The initial Blazor Web App used "Global Interactivity" because per-page/component interactivity is not compatible with Blazor Hybrid
