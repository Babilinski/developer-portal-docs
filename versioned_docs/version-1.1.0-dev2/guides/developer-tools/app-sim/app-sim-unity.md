---
id: app-sim-unity
title: Configure Unity for Application Simulator
sidebar_position: 9
date: 08/29/2022
tags: [Application Simulator, Unity]
keywords: [Application Simulator, Unity]
---

export const Lowercase = ({children}) => (
  <span
    style={{
      textTransform: 'lowercase',
    }}>
    {children}
  </span>
);

In order to play scenes against Application Simulator in the Unity editor, you must first install and configure Unity for Magic Leap 2. Follow the [Unity Getting Started Guide](/versioned_docs/version-1.1.0-dev2/guides/unity/getting-started/unity-getting-started.md) and the [Configure Unity Settings Guide](/versioned_docs/version-1.1.0-dev2/guides/unity/getting-started/configure-unity-settings.md) for set-up instructions.

## Playing the Scene

Start [**Application Simulator**](/versioned_docs/version-1.1.0-dev2/guides/developer-tools/app-sim/using-app-sim.md) in ML Hub, connect to **Simulator**, and click **Play** in Unity. You should now be able to see the scene simultaneously being played in Unity and rendered in the **Device View** in Application Simulator.

You are also encouraged to try out the [**Unity Examples** project](/versioned_docs/version-1.1.0-dev2/guides/unity/sdk-example-scenes/sdk-install-setup.md), found in the ML Hub's [package manager](/versioned_docs/version-1.1.0-dev2/guides/developer-tools/ml-hub/ml-hub-package-manager.md). The project contains several scenes demonstrating key Magic Leap 2 features. You can find which features are currently compatible with Application Simulator by referencing the [Application Simulator Key API](/versioned_docs/version-1.1.0-dev2/guides/developer-tools/app-sim/app-sim-key-api-features.md) charts.

:::caution <Lowercase>mac</Lowercase>OS

If you are using the Metal graphics API, you must upgrade the `com.unity.xr.magicleap` package to version `7.0.0-exp.5` in order for the Application Simulator to work with Unity.
You can do so by going to **Window > Package Manager > Magic Leap XR Plugin** and select "Version History" to locate version `7.0.0-exp.5` and click **Update**.

See [Magic Leap App Simulator Graphics Compatibility](/versioned_docs/version-1.1.0-dev2/guides/developer-tools/app-sim/app-sim-graphics-compatibility.md).  

:::
