﻿# Power App Documentation \- App\_GymTrend\_Mobile

| Property                   | Value                                   |
| -------------------------- | --------------------------------------- |
| App Name                   | App\_GymTrend\_Mobile                   |
| App Logo                   | ![App Logo](resources/applogoSmall.png) |
| Documentation generated at | Wednesday, April 17, 2024 10:56 AM      |

- [Overview](index-App_GymTrend_Mobile.md)
- [App Details](appdetails-App_GymTrend_Mobile.md)
- [Variables](variables-App_GymTrend_Mobile.md)
- [DataSources](datasources-App_GymTrend_Mobile.md)
- [Resources](resources-App_GymTrend_Mobile.md)
- [Controls](controls-App_GymTrend_Mobile.md)

## Checks\_List

| Property                        | Value        |
| ------------------------------- | ------------ |
| ![screen](resources/screen.png) | Type: screen |

### Behavior

| Property  | Value                                                                                                                                                                            |
| --------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnVisible | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">UpdateContext({varCamera:varCamera+1})<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                           |
| ------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Height              | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1136<td style="background-color:#ffcccc; width:50%;">Max(App.Height, App.MinScreenHeight)</td></tr></table>                                                                                                                                                                                                                              |
| ImagePosition       | ImagePosition.Fit                                                                                                                                                                                                                                                                                                                                                                                               |
| LoadingSpinner      | LoadingSpinner.None                                                                                                                                                                                                                                                                                                                                                                                             |
| LoadingSpinnerColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 120, 212, 1)</td></tr><tr><td style="background-color:#0078D4"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table></td></tr></table> |
| Orientation         | If(Self.Width \< Self.Height, Layout.Vertical, Layout.Horizontal)                                                                                                                                                                                                                                                                                                                                               |
| Size                | 1 + CountRows(App.SizeBreakpoints) \- CountIf(App.SizeBreakpoints, Value \>\= Self.Width)                                                                                                                                                                                                                                                                                                                       |
| Width               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">640<td style="background-color:#ffcccc; width:50%;">Max(App.Width, App.MinScreenWidth)</td></tr></table>                                                                                                                                                                                                                                 |

### Color Properties

| Property | Value                                                                                                                                                                                                                                                                                                                                                                                              |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Fill     | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>White</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property      | Value           |
| ------------- | --------------- |
| Child Control | cnt\_main\_4    |
| Child Control | msft\_Button\_2 |

## cnt\_footer\_4

| Property                                                                  | Value                             |
| ------------------------------------------------------------------------- | --------------------------------- |
| ![verticalAutoLayoutContainer](resources/verticalAutoLayoutContainer.png) | Type: verticalAutoLayoutContainer |

### Data

| Property        | Value |
| --------------- | ----- |
| ContentLanguage |       |

### Design

| Property             | Value                                                                                                                                                              |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                     |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.Light<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">cnt_header_4.Height/2<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>   |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Vertical<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.End<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| X                    | 0                                                                                                                                                                  |
| Y                    | 0                                                                                                                                                                  |
| ZIndex               | 3                                                                                                                                                                  |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | ColorValue("\#FC417B")                                                                                                                                                                                                                                                                                                               |

### Child & Parent Controls

| Property       | Value        |
| -------------- | ------------ |
| Child Control  | Footer\_5    |
| Parent Control | cnt\_main\_4 |

## cnt\_header\_4

| Property                                                                  | Value                             |
| ------------------------------------------------------------------------- | --------------------------------- |
| ![verticalAutoLayoutContainer](resources/verticalAutoLayoutContainer.png) | Type: verticalAutoLayoutContainer |

### Data

| Property        | Value                                                                                                                                                  |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property             | Value                                                                                                                                                                |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.Light<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">80<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Vertical<td style="background-color:#ffcccc; width:50%;"></td></tr></table>   |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| PaddingLeft          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">637<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| X                    | 0                                                                                                                                                                    |
| Y                    | 0                                                                                                                                                                    |
| ZIndex               | 1                                                                                                                                                                    |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | ColorValue("\#143454")                                                                                                                                                                                                                                                                                                               |

### Child & Parent Controls

| Property       | Value        |
| -------------- | ------------ |
| Child Control  | Header\_7    |
| Parent Control | cnt\_main\_4 |

## cnt\_main\_4

| Property                                                                  | Value                             |
| ------------------------------------------------------------------------- | --------------------------------- |
| ![verticalAutoLayoutContainer](resources/verticalAutoLayoutContainer.png) | Type: verticalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.Light<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Vertical<td style="background-color:#ffcccc; width:50%;"></td></tr></table>   |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| X                    | 3                                                                                                                                                                    |
| Y                    | 3                                                                                                                                                                    |
| ZIndex               | 1                                                                                                                                                                    |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                      |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Child Control  | cnt\_header\_4 |
| Child Control  | cnt\-body\_4   |
| Child Control  | cnt\_footer\_4 |
| Parent Control | Checks\_List   |

## cnt\-body\_4

| Property                                                      | Value                       |
| ------------------------------------------------------------- | --------------------------- |
| ![manualLayoutContainer](resources/manualLayoutContainer.png) | Type: manualLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.Light<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">225<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Horizontal<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Manual<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">500<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| X                    | 0                                                                                                                                                                    |
| Y                    | 0                                                                                                                                                                    |
| ZIndex               | 2                                                                                                                                                                    |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value        |
| -------------- | ------------ |
| Child Control  | Gallery3     |
| Parent Control | cnt\_main\_4 |

## Footer\_5

| Property                              | Value           |
| ------------------------------------- | --------------- |
| ![component](resources/component.png) | Type: component |

### Design

| Property | Value                                                                                                                                         |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| Height   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">40<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| Width    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">640<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| X        | 0                                                                                                                                             |
| Y        | 0                                                                                                                                             |
| ZIndex   | 2                                                                                                                                             |

### Color Properties

| Property | Value                                                                                                                                                                                                                                                                                                                                |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Fill     | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | cnt\_footer\_4 |

## Gallery3

| Property                          | Value         |
| --------------------------------- | ------------- |
| ![gallery](resources/gallery.png) | Type: gallery |

### Data

| Property  | Value                                                                                                                                                                                                     |
| --------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Items     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Filter('Gym Maintenance Log',Local=varLocal)<td style="background-color:#ffcccc; width:50%;">CustomGallerySample</td></tr></table> |
| WrapCount | 1                                                                                                                                                                                                         |

### Design

| Property            | Value                                                                                                                                                                            |
| ------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle         | BorderStyle.Solid                                                                                                                                                                |
| DelayItemLoading    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                   |
| DisplayMode         | DisplayMode.Edit                                                                                                                                                                 |
| Height              | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">837<td style="background-color:#ffcccc; width:50%;">575</td></tr></table>                                 |
| Layout              | Layout.Vertical                                                                                                                                                                  |
| LoadingSpinner      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LoadingSpinner.Data<td style="background-color:#ffcccc; width:50%;">LoadingSpinner.None</td></tr></table> |
| LoadingSpinnerColor | Self.BorderColor                                                                                                                                                                 |
| TemplatePadding     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">5<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                     |
| TemplateSize        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">96<td style="background-color:#ffcccc; width:50%;">Min(160, Self.Height - 60)</td></tr></table>           |
| Transition          | Transition.None                                                                                                                                                                  |
| Width               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width<td style="background-color:#ffcccc; width:50%;">640</td></tr></table>                        |
| X                   | 0                                                                                                                                                                                |
| Y                   | 15                                                                                                                                                                               |
| ZIndex              | 1                                                                                                                                                                                |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                            |
| ------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table> |
| DisabledBorderColor | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                 |
| DisabledFill        | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                        |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                  |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                 |
| HoverBorderColor    | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                 |
| HoverFill           | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                        |
| PressedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                 |
| PressedFill         | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                        |

### Child & Parent Controls

| Property       | Value            |
| -------------- | ---------------- |
| Child Control  | galleryTemplate3 |
| Child Control  | Icon9            |
| Child Control  | Label7           |
| Child Control  | Toggle1          |
| Parent Control | cnt\-body\_4     |

## galleryTemplate3

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![galleryTemplate](resources/galleryTemplate.png) | Type: galleryTemplate |

### Design

| Property     | Value                                                                                                                                                                                                                                                                                                                                |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| TemplateFill | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Color Properties

### Child & Parent Controls

| Property       | Value    |
| -------------- | -------- |
| Parent Control | Gallery3 |

## Header\_7

| Property                              | Value           |
| ------------------------------------- | --------------- |
| ![component](resources/component.png) | Type: component |

### Behavior

| Property        | Value                                                                                                                                                  |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Gym\_Management | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Checks_Local<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Home            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Home<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |

### Design

| Property | Value                                                                                                                                         |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| Height   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">80<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| Width    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">640<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| X        | 0                                                                                                                                             |
| Y        | 0                                                                                                                                             |
| ZIndex   | 1                                                                                                                                             |

### Color Properties

| Property | Value                                                                                                                                                                                                                                                                                                                                |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Fill     | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | cnt\_header\_4 |

## Icon9

| Property                    | Value      |
| --------------------------- | ---------- |
| ![icon](resources/icon.png) | Type: icon |

### Behavior

| Property | Value                                                                                                                                                                                     |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Navigate(Gym_Management); Set(varItem,ThisItem)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                                  |
| ---------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                            |
| DisplayMode            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                             |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                            |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">64<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                           |
| Icon                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Icon.Camera<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                  |
| Visible                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Text(ThisItem.HasPhoto)="Sim",true,false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">64<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                           |
| X                      | 40                                                                                                                                                                                     |
| Y                      | 40                                                                                                                                                                                     |
| ZIndex                 | 1                                                                                                                                                                                      |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                      |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Color               | If(IsBlank(LookUp(ItemsRegisters, Item \= ThisItem.Itens\_Check).Item),RGBA(29,157,255,1),Color.DarkGray)                                                                                                                                                                                                                                  |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(220, 220, 220, 1)</td></tr><tr><td style="background-color:#DCDCDC"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| Fill                | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                           |
| HoverBorderColor    | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| HoverColor          | ColorFade(RGBA(0, 120, 212, 1), \-30%)                                                                                                                                                                                                                                                                                                     |
| HoverFill           | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| PressedBorderColor  | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| PressedColor        | ColorFade(RGBA(0, 120, 212, 1), \-30%)                                                                                                                                                                                                                                                                                                     |
| PressedFill         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |

### Child & Parent Controls

| Property       | Value    |
| -------------- | -------- |
| Parent Control | Gallery3 |

## Label7

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Behavior

| Property | Value                                                                                                                                                    |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Select(Parent)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property | Value                                                                                                                                                                |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Live     | Live.Off                                                                                                                                                             |
| Role     | TextRole.Default                                                                                                                                                     |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.Itens_Check<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                       |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align                  | Align.Left                                                                                                                                                                  |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table> |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                            |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                |
| Font                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Font.'Segoe UI'<td style="background-color:#ffcccc; width:50%;">Font.'Open Sans'</td></tr></table>   |
| FontWeight             | FontWeight.Normal                                                                                                                                                           |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">60<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                              |
| Italic                 | false                                                                                                                                                                       |
| LineHeight             | 1.2                                                                                                                                                                         |
| Overflow               | Overflow.Hidden                                                                                                                                                             |
| PaddingBottom          | 5                                                                                                                                                                           |
| PaddingLeft            | 5                                                                                                                                                                           |
| PaddingRight           | 5                                                                                                                                                                           |
| PaddingTop             | 5                                                                                                                                                                           |
| Size                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">21<td style="background-color:#ffcccc; width:50%;">13</td></tr></table>                              |
| Strikethrough          | false                                                                                                                                                                       |
| Underline              | false                                                                                                                                                                       |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                        |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">482<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>                            |
| X                      | 126                                                                                                                                                                         |
| Y                      | 42                                                                                                                                                                          |
| ZIndex                 | 2                                                                                                                                                                           |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                      |
| ------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table> |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(51, 51, 51, 1)</td></tr><tr><td style="background-color:#333333"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table> |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table></td></tr></table> |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table>                                                                                                                                                                                                                                                                                      |
| DisabledFill        | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                            |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                            |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                           |
| HoverBorderColor    | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                           |
| HoverColor          | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                 |
| HoverFill           | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                  |
| PressedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                           |
| PressedColor        | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                 |
| PressedFill         | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                  |

### Child & Parent Controls

| Property       | Value    |
| -------------- | -------- |
| Parent Control | Gallery3 |

## msft\_Button\_2

| Property                        | Value        |
| ------------------------------- | ------------ |
| ![button](resources/button.png) | Type: button |

### Behavior

| Property | Value                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">/* If(And(IsBlank(username.Text),IsBlank(password.Text)),false, If( //Or(username.Text = LookUp(UsersInfo, Username = username.Text).username,username.Text = LookUp(UsersInfo, Email = Username.Text).Email) - se tivessemos coluna email username.Text = LookUp(UsersInfo, Username = username.Text).Username && password.Text = LookUp(UsersInfo, Username = username.Text).Passwords, Navigate(Home,ScreenTransition.Fade,{Varusername: username.Text}), Set(Varusername,username.Text) ); Reset(username)&Reset(password)) */ Patch(ItemsRegisters, Defaults(ItemsRegisters), { Local: varItem.Local, Item: varItem.Itens_Check, Toggle: Toggle1.Value } ); Clear(Fotos); Refresh(Manutencaos); //Navigate(Checks_Local,ScreenTransition.Fade)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property        | Value                                                                                                                                                              |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| Text            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Enviar registo"<td style="background-color:#ffcccc; width:50%;">"Button"</td></tr></table> |
| Tooltip         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Inicar Sessão"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |

### Design

| Property               | Value                                                                                                                                                                           |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align                  | Align.Center                                                                                                                                                                    |
| AutoDisableOnSelect    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                  |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table>     |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1<td style="background-color:#ffcccc; width:50%;">2</td></tr></table>                                    |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                                |
| FocusedBorderThickness | 4                                                                                                                                                                               |
| Font                   | Font.'Open Sans'                                                                                                                                                                |
| FontWeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">FontWeight.Normal<td style="background-color:#ffcccc; width:50%;">FontWeight.Semibold</td></tr></table>  |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">65<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                                  |
| Italic                 | false                                                                                                                                                                           |
| maximumHeight          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">768<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                   |
| maximumWidth           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1366<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                  |
| minimumHeight          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">5<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| minimumWidth           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">5<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| PaddingBottom          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">5<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">56<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                    |
| PaddingRight           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">56<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                    |
| PaddingTop             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                    |
| RadiusBottomLeft       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">80<td style="background-color:#ffcccc; width:50%;">10</td></tr></table>                                  |
| RadiusBottomRight      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">80<td style="background-color:#ffcccc; width:50%;">10</td></tr></table>                                  |
| RadiusTopLeft          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">80<td style="background-color:#ffcccc; width:50%;">10</td></tr></table>                                  |
| RadiusTopRight         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">80<td style="background-color:#ffcccc; width:50%;">10</td></tr></table>                                  |
| Size                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">26.25<td style="background-color:#ffcccc; width:50%;">15</td></tr></table>                               |
| Strikethrough          | false                                                                                                                                                                           |
| TabIndex               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| Underline              | false                                                                                                                                                                           |
| VerticalAlign          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">VerticalAlign.Top<td style="background-color:#ffcccc; width:50%;">VerticalAlign.Middle</td></tr></table> |
| Visible                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                  |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">342<td style="background-color:#ffcccc; width:50%;">160</td></tr></table>                                |
| X                      | 152                                                                                                                                                                             |
| Y                      | 972                                                                                                                                                                             |
| ZIndex                 | 2                                                                                                                                                                               |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                                   |
| ------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.Fill, -15%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>       |
| Color               | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table>                                                                                                                                                                                                                                                                                                   |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table>           |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table>                                                                                                                                                                                                                                                                                                   |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table>                                                                                                                                                                                                                                                                                                   |
| Fill                | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(20, 52, 84, 1)</td></tr><tr><td style="background-color:#143454"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table></td></tr></table>          |
| FocusedBorderColor  | ColorFade(Self.Fill, \-75%)                                                                                                                                                                                                                                                                                                                                                                                             |
| HoverBorderColor    | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.BorderColor, 20%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table> |
| HoverColor          | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table>                                                                                                                                                                                                                                                                                                   |
| HoverFill           | ColorFade(RGBA(0, 120, 212, 1), \-10%)                                                                                                                                                                                                                                                                                                                                                                                  |
| PressedBorderColor  | ColorFade(RGBA(0, 120, 212, 1), \-50%)                                                                                                                                                                                                                                                                                                                                                                                  |
| PressedColor        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.Fill</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>                  |
| PressedFill         | ColorFade(RGBA(0, 120, 212, 1), \-30%)                                                                                                                                                                                                                                                                                                                                                                                  |

### Child & Parent Controls

| Property       | Value        |
| -------------- | ------------ |
| Parent Control | Checks\_List |

## Toggle1

| Property                                    | Value              |
| ------------------------------------------- | ------------------ |
| ![toggleSwitch](resources/toggleSwitch.png) | Type: toggleSwitch |

### Behavior

| Property | Value                                                                                                                                                    |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Select(Parent)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                                                                                                                                                                                                                                                                    |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table>                                                                                                                                                                                                                                              |
| BorderThickness        | 0                                                                                                                                                                                                                                                                                                                                                                                                                        |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                                                                                                                                                                                                                                                                         |
| FalseFill              | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(252, 65, 123, 1)</td></tr><tr><td style="background-color:#FC417B"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(128, 130, 133, 1)</td></tr><tr><td style="background-color:#808285"></td></tr></table></td></tr></table>       |
| FalseHoverFill         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(33, 33, 33, 1)</td></tr><tr><td style="background-color:#212121"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.FalseFill, 15%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table> |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;">2</td></tr></table>                                                                                                                                                                                                                                                                             |
| Font                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Font.'Segoe UI'<td style="background-color:#ffcccc; width:50%;">Font.'Open Sans'</td></tr></table>                                                                                                                                                                                                                                                |
| FontWeight             | FontWeight.Normal                                                                                                                                                                                                                                                                                                                                                                                                        |
| HandleFill             | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table>                                                                                                                                                                                                                                                                                                    |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">47<td style="background-color:#ffcccc; width:50%;">28</td></tr></table>                                                                                                                                                                                                                                                                           |
| ShowLabel              | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                                                                                                                                                                                          |
| Size                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">21<td style="background-color:#ffcccc; width:50%;">13</td></tr></table>                                                                                                                                                                                                                                                                           |
| TextPosition           | TextPosition.Right                                                                                                                                                                                                                                                                                                                                                                                                       |
| TrueFill               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 120, 212, 1)</td></tr><tr><td style="background-color:#0078D4"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table></td></tr></table>          |
| TrueHoverFill          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ColorFade(RGBA(0, 120, 212, 1), -30%)<td style="background-color:#ffcccc; width:50%;">ColorFade(Self.TrueFill, 15%)</td></tr></table>                                                                                                                                                                                                             |
| Visible                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                                                                                                                                                                                           |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">104<td style="background-color:#ffcccc; width:50%;">92</td></tr></table>                                                                                                                                                                                                                                                                          |
| X                      | 526                                                                                                                                                                                                                                                                                                                                                                                                                      |
| Y                      | 42                                                                                                                                                                                                                                                                                                                                                                                                                       |
| ZIndex                 | 3                                                                                                                                                                                                                                                                                                                                                                                                                        |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                                    |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>               |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(51, 51, 51, 1)</td></tr><tr><td style="background-color:#333333"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>               |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table></td></tr></table>               |
| DisabledColor       | <table border="0"><tr><td>RGBA(186, 186, 186, 1)</td></tr><tr><td style="background-color:#BABABA"></td></tr></table>                                                                                                                                                                                                                                                                                                    |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                         |
| HoverBorderColor    | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.BorderColor, 15%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>  |
| PressedBorderColor  | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.BorderColor, -15%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value    |
| -------------- | -------- |
| Parent Control | Gallery3 |
