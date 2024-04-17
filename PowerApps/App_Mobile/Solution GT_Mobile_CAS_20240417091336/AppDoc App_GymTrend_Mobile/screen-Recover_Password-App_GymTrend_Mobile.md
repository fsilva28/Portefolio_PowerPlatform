# Power App Documentation \- App\_GymTrend\_Mobile

| Property                   | Value                                   |
| -------------------------- | --------------------------------------- |
| App Name                   | App\_GymTrend\_Mobile                   |
| App Logo                   | ![App Logo](resources/applogoSmall.png) |
| Documentation generated at | 17 de abril de 2024 11:14               |

- [Overview](index-App_GymTrend_Mobile.md)
- [App Details](appdetails-App_GymTrend_Mobile.md)
- [Variables](variables-App_GymTrend_Mobile.md)
- [DataSources](datasources-App_GymTrend_Mobile.md)
- [Resources](resources-App_GymTrend_Mobile.md)
- [Controls](controls-App_GymTrend_Mobile.md)

## Recover\_Password

| Property                        | Value        |
| ------------------------------- | ------------ |
| ![screen](resources/screen.png) | Type: screen |

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
| Child Control | cnt\_main\_1    |
| Child Control | Label6          |
| Child Control | Label5          |
| Child Control | Label5\_1       |
| Child Control | msft\_Button\_1 |

## cnt\_footer\_1

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
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">cnt_header_1.Height/2<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
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
| Child Control  | Footer\_1    |
| Parent Control | cnt\_main\_1 |

## cnt\_header\_1

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
| Child Control  | Header\_1    |
| Parent Control | cnt\_main\_1 |

## cnt\_main\_1

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

| Property       | Value             |
| -------------- | ----------------- |
| Child Control  | cnt\_header\_1    |
| Child Control  | cnt\-body\_1      |
| Child Control  | cnt\_footer\_1    |
| Parent Control | Recover\_Password |

## cnt\-body\_1

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
| Child Control  | Label4       |
| Child Control  | Label1\_1    |
| Child Control  | password\_1  |
| Child Control  | password\_2  |
| Parent Control | cnt\_main\_1 |

## Footer\_1

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
| Parent Control | cnt\_footer\_1 |

## Header\_1

| Property                              | Value           |
| ------------------------------------- | --------------- |
| ![component](resources/component.png) | Type: component |

### Behavior

| Property        | Value                                                                                                                                                    |
| --------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Gym\_Management | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Checks_Local<td style="background-color:#ffcccc; width:50%;"></td></tr></table>   |
| Home            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Navigate(Home)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property | Value                                                                                                                                           |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| Height   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">80<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| Visible  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">640<td style="background-color:#ffcccc; width:50%;"></td></tr></table>   |
| X        | 0                                                                                                                                               |
| Y        | 0                                                                                                                                               |
| ZIndex   | 2                                                                                                                                               |

### Color Properties

| Property | Value                                                                                                                                                                                                                                                                                                                                |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Fill     | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | cnt\_header\_1 |

## Label1\_1

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property | Value                                                                                                                                                                                                                                |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Live     | Live.Off                                                                                                                                                                                                                             |
| Role     | TextRole.Default                                                                                                                                                                                                                     |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Nova password para a conta: " & LookUp(UsersInfo,Username = username.Text,Username)<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                       |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Align.Center<td style="background-color:#ffcccc; width:50%;">Align.Left</td></tr></table>            |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table> |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                            |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                |
| Font                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Font.'Segoe UI'<td style="background-color:#ffcccc; width:50%;">Font.'Open Sans'</td></tr></table>   |
| FontWeight             | FontWeight.Normal                                                                                                                                                           |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">94<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                              |
| Italic                 | false                                                                                                                                                                       |
| LineHeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1.5<td style="background-color:#ffcccc; width:50%;">1.2</td></tr></table>                            |
| Overflow               | Overflow.Hidden                                                                                                                                                             |
| PaddingBottom          | 5                                                                                                                                                                           |
| PaddingLeft            | 5                                                                                                                                                                           |
| PaddingRight           | 5                                                                                                                                                                           |
| PaddingTop             | 5                                                                                                                                                                           |
| Size                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">18<td style="background-color:#ffcccc; width:50%;">13</td></tr></table>                              |
| Strikethrough          | false                                                                                                                                                                       |
| Underline              | false                                                                                                                                                                       |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                        |
| Visible                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                              |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">560<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>                            |
| X                      | 40                                                                                                                                                                          |
| Y                      | 178                                                                                                                                                                         |
| ZIndex                 | 1                                                                                                                                                                           |

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

| Property       | Value        |
| -------------- | ------------ |
| Parent Control | cnt\-body\_1 |

## Label4

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property | Value                                                                                                                                                                |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Live     | Live.Off                                                                                                                                                             |
| Role     | TextRole.Default                                                                                                                                                     |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Recuperar Password"<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                       |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Align.Center<td style="background-color:#ffcccc; width:50%;">Align.Left</td></tr></table>            |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table> |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                            |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                |
| Font                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Font.'Segoe UI'<td style="background-color:#ffcccc; width:50%;">Font.'Open Sans'</td></tr></table>   |
| FontWeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">FontWeight.Bold<td style="background-color:#ffcccc; width:50%;">FontWeight.Normal</td></tr></table>  |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">80<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                              |
| Italic                 | false                                                                                                                                                                       |
| LineHeight             | 1.2                                                                                                                                                                         |
| Overflow               | Overflow.Hidden                                                                                                                                                             |
| PaddingBottom          | 5                                                                                                                                                                           |
| PaddingLeft            | 5                                                                                                                                                                           |
| PaddingRight           | 5                                                                                                                                                                           |
| PaddingTop             | 5                                                                                                                                                                           |
| Size                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">26<td style="background-color:#ffcccc; width:50%;">13</td></tr></table>                              |
| Strikethrough          | false                                                                                                                                                                       |
| Underline              | false                                                                                                                                                                       |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                        |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">364<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>                            |
| X                      | 138                                                                                                                                                                         |
| Y                      | 74                                                                                                                                                                          |
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

| Property       | Value        |
| -------------- | ------------ |
| Parent Control | cnt\-body\_1 |

## Label5

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property | Value                                                                                                                                                            |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Live     | Live.Off                                                                                                                                                         |
| Role     | TextRole.Default                                                                                                                                                 |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Nova password:"<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                          |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Align                  | Align.Left                                                                                                                                                                     |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table>    |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                   |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                               |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                   |
| Font                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Font.'Segoe UI'<td style="background-color:#ffcccc; width:50%;">Font.'Open Sans'</td></tr></table>      |
| FontWeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">FontWeight.Semibold<td style="background-color:#ffcccc; width:50%;">FontWeight.Normal</td></tr></table> |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">64<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                                 |
| Italic                 | false                                                                                                                                                                          |
| LineHeight             | 1.2                                                                                                                                                                            |
| Overflow               | Overflow.Hidden                                                                                                                                                                |
| PaddingBottom          | 5                                                                                                                                                                              |
| PaddingLeft            | 5                                                                                                                                                                              |
| PaddingRight           | 5                                                                                                                                                                              |
| PaddingTop             | 5                                                                                                                                                                              |
| Size                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">21<td style="background-color:#ffcccc; width:50%;">13</td></tr></table>                                 |
| Strikethrough          | false                                                                                                                                                                          |
| Underline              | false                                                                                                                                                                          |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                           |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">234<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>                               |
| X                      | 43                                                                                                                                                                             |
| Y                      | 433                                                                                                                                                                            |
| ZIndex                 | 2                                                                                                                                                                              |

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

| Property       | Value             |
| -------------- | ----------------- |
| Parent Control | Recover\_Password |

## Label5\_1

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property | Value                                                                                                                                                                      |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Live     | Live.Off                                                                                                                                                                   |
| Role     | TextRole.Default                                                                                                                                                           |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Confirmar nova password:"<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                          |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Align                  | Align.Left                                                                                                                                                                     |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table>    |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                   |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                               |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                   |
| Font                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Font.'Segoe UI'<td style="background-color:#ffcccc; width:50%;">Font.'Open Sans'</td></tr></table>      |
| FontWeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">FontWeight.Semibold<td style="background-color:#ffcccc; width:50%;">FontWeight.Normal</td></tr></table> |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">66<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                                 |
| Italic                 | false                                                                                                                                                                          |
| LineHeight             | 1.2                                                                                                                                                                            |
| Overflow               | Overflow.Hidden                                                                                                                                                                |
| PaddingBottom          | 5                                                                                                                                                                              |
| PaddingLeft            | 5                                                                                                                                                                              |
| PaddingRight           | 5                                                                                                                                                                              |
| PaddingTop             | 5                                                                                                                                                                              |
| Size                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">21<td style="background-color:#ffcccc; width:50%;">13</td></tr></table>                                 |
| Strikethrough          | false                                                                                                                                                                          |
| Underline              | false                                                                                                                                                                          |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                           |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">462<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>                               |
| X                      | 43                                                                                                                                                                             |
| Y                      | 600                                                                                                                                                                            |
| ZIndex                 | 3                                                                                                                                                                              |

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

| Property       | Value             |
| -------------- | ----------------- |
| Parent Control | Recover\_Password |

## Label6

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property | Value                                                                                                                                                       |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Live     | Live.Off                                                                                                                                                    |
| Role     | TextRole.Default                                                                                                                                            |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Varusername<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                       |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Align.Center<td style="background-color:#ffcccc; width:50%;">Align.Left</td></tr></table>            |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table> |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                |
| DisplayMode            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.View<td style="background-color:#ffcccc; width:50%;">DisplayMode.Edit</td></tr></table>  |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                |
| Font                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Font.'Segoe UI'<td style="background-color:#ffcccc; width:50%;">Font.'Open Sans'</td></tr></table>   |
| FontWeight             | FontWeight.Normal                                                                                                                                                           |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">66<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                              |
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
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">544<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>                            |
| X                      | 43                                                                                                                                                                          |
| Y                      | 340                                                                                                                                                                         |
| ZIndex                 | 5                                                                                                                                                                           |

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

| Property       | Value             |
| -------------- | ----------------- |
| Parent Control | Recover\_Password |

## msft\_Button\_1

| Property                        | Value        |
| ------------------------------- | ------------ |
| ![button](resources/button.png) | Type: button |

### Behavior

| Property | Value                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">UpdateIf( UsersInfo, Username = Varusername, { Passwords: password_2.Text } ); Refresh(UsersInfo); If( LookUp( UsersInfo, Username = Varusername, Passwords) = password_2.Text, Notify("Password actualizada com sucesso",NotificationType.Success)&Navigate(Home), Notify("Algo correu mal :/",NotificationType.Error)&Navigate(Login) ); Reset(password_1)&Reset(password_2)&Set(Varusername,Blank());<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property        | Value                                                                                                                                                                  |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| Text            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Recuperar Password"<td style="background-color:#ffcccc; width:50%;">"Button"</td></tr></table> |
| Tooltip         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |

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
| PaddingBottom          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">12<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                    |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">56<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                    |
| PaddingRight           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">56<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                    |
| PaddingTop             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">11<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                    |
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
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">464<td style="background-color:#ffcccc; width:50%;">160</td></tr></table>                                |
| X                      | 91                                                                                                                                                                              |
| Y                      | 837                                                                                                                                                                             |
| ZIndex                 | 4                                                                                                                                                                               |

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

| Property       | Value             |
| -------------- | ----------------- |
| Parent Control | Recover\_Password |

## password\_1

| Property                    | Value      |
| --------------------------- | ---------- |
| ![text](resources/text.png) | Type: text |

### Behavior

| Property | Value                                                                                                                                           |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| OnChange | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property        | Value                                                                                                                                                       |
| --------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| AccessibleLabel | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Default         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;"><td style="background-color:#ffcccc; width:50%;">"Text input"</td></tr></table>      |
| DelayOutput     | false                                                                                                                                                       |
| HintText        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Insira password"<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| MaxLength       |                                                                                                                                                             |
| Reset           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| Tooltip         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |

### Design

| Property               | Value                                                                                                                                                                          |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Align                  | Align.Left                                                                                                                                                                     |
| BorderStyle            | BorderStyle.Solid                                                                                                                                                              |
| BorderThickness        | 2                                                                                                                                                                              |
| Clear                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                               |
| EnableSpellCheck       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                |
| FocusedBorderThickness | 4                                                                                                                                                                              |
| Font                   | Font.'Open Sans'                                                                                                                                                               |
| FontWeight             | FontWeight.Normal                                                                                                                                                              |
| Format                 | TextFormat.Text                                                                                                                                                                |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">70<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                                 |
| Italic                 | false                                                                                                                                                                          |
| LineHeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1.132813<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                             |
| maximumHeight          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">768<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                  |
| maximumWidth           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1366<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| minimumHeight          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                   |
| minimumWidth           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                   |
| Mode                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">TextMode.Password<td style="background-color:#ffcccc; width:50%;">TextMode.SingleLine</td></tr></table> |
| PaddingBottom          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">15<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                   |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                   |
| PaddingRight           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                   |
| PaddingTop             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">15<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                   |
| RadiusBottomLeft       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">80<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                  |
| RadiusBottomRight      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">80<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                  |
| RadiusTopLeft          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">80<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                  |
| RadiusTopRight         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">80<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                  |
| Size                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">18<td style="background-color:#ffcccc; width:50%;">13</td></tr></table>                                 |
| Strikethrough          | false                                                                                                                                                                          |
| TabIndex               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                    |
| Underline              | false                                                                                                                                                                          |
| VirtualKeyboardMode    | VirtualKeyboardMode.Auto                                                                                                                                                       |
| Visible                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">560<td style="background-color:#ffcccc; width:50%;">320</td></tr></table>                               |
| X                      | 40                                                                                                                                                                             |
| Y                      | 420                                                                                                                                                                            |
| ZIndex                 | 3                                                                                                                                                                              |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>    |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>       |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table>       |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table>                                                                                                                                                                                                                                                                                               |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table>                                                                                                                                                                                                                                                                                               |
| Fill                | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table>                                                                                                                                                                                                                                                                                               |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverBorderColor    | ColorFade(RGBA(0, 120, 212, 1), \-30%)                                                                                                                                                                                                                                                                                                                                                                              |
| HoverColor          | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(51, 51, 51, 1)</td></tr><tr><td style="background-color:#333333"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>          |
| HoverFill           | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(186, 202, 226, 1)</td></tr><tr><td style="background-color:#BACAE2"></td></tr></table></td></tr></table> |
| PressedBorderColor  | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 120, 212, 1)</td></tr><tr><td style="background-color:#0078D4"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.HoverBorderColor</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>    |
| PressedColor        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(51, 51, 51, 1)</td></tr><tr><td style="background-color:#333333"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.Color</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>                |
| PressedFill         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.Fill</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>              |

### Child & Parent Controls

| Property       | Value        |
| -------------- | ------------ |
| Parent Control | cnt\-body\_1 |

## password\_2

| Property                    | Value      |
| --------------------------- | ---------- |
| ![text](resources/text.png) | Type: text |

### Behavior

| Property | Value                                                                                                                                           |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| OnChange | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property        | Value                                                                                                                                                       |
| --------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| AccessibleLabel | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Default         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;"><td style="background-color:#ffcccc; width:50%;">"Text input"</td></tr></table>      |
| DelayOutput     | false                                                                                                                                                       |
| HintText        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Insira password"<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| MaxLength       |                                                                                                                                                             |
| Reset           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| Tooltip         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |

### Design

| Property               | Value                                                                                                                                                                          |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Align                  | Align.Left                                                                                                                                                                     |
| BorderStyle            | BorderStyle.Solid                                                                                                                                                              |
| BorderThickness        | 2                                                                                                                                                                              |
| Clear                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                               |
| EnableSpellCheck       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                |
| FocusedBorderThickness | 4                                                                                                                                                                              |
| Font                   | Font.'Open Sans'                                                                                                                                                               |
| FontWeight             | FontWeight.Normal                                                                                                                                                              |
| Format                 | TextFormat.Text                                                                                                                                                                |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">70<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                                 |
| Italic                 | false                                                                                                                                                                          |
| LineHeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1.132813<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                             |
| maximumHeight          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">768<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                  |
| maximumWidth           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1366<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| minimumHeight          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                   |
| minimumWidth           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                   |
| Mode                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">TextMode.Password<td style="background-color:#ffcccc; width:50%;">TextMode.SingleLine</td></tr></table> |
| PaddingBottom          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">15<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                   |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                   |
| PaddingRight           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                   |
| PaddingTop             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">15<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                   |
| RadiusBottomLeft       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">80<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                  |
| RadiusBottomRight      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">80<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                  |
| RadiusTopLeft          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">80<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                  |
| RadiusTopRight         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">80<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                  |
| Size                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">18<td style="background-color:#ffcccc; width:50%;">13</td></tr></table>                                 |
| Strikethrough          | false                                                                                                                                                                          |
| TabIndex               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                    |
| Underline              | false                                                                                                                                                                          |
| VirtualKeyboardMode    | VirtualKeyboardMode.Auto                                                                                                                                                       |
| Visible                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">560<td style="background-color:#ffcccc; width:50%;">320</td></tr></table>                               |
| X                      | 40                                                                                                                                                                             |
| Y                      | 584                                                                                                                                                                            |
| ZIndex                 | 4                                                                                                                                                                              |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>    |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>       |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table>       |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table>                                                                                                                                                                                                                                                                                               |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table>                                                                                                                                                                                                                                                                                               |
| Fill                | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table>                                                                                                                                                                                                                                                                                               |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverBorderColor    | ColorFade(RGBA(0, 120, 212, 1), \-30%)                                                                                                                                                                                                                                                                                                                                                                              |
| HoverColor          | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(51, 51, 51, 1)</td></tr><tr><td style="background-color:#333333"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>          |
| HoverFill           | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(186, 202, 226, 1)</td></tr><tr><td style="background-color:#BACAE2"></td></tr></table></td></tr></table> |
| PressedBorderColor  | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 120, 212, 1)</td></tr><tr><td style="background-color:#0078D4"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.HoverBorderColor</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>    |
| PressedColor        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(51, 51, 51, 1)</td></tr><tr><td style="background-color:#333333"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.Color</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>                |
| PressedFill         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.Fill</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>              |

### Child & Parent Controls

| Property       | Value        |
| -------------- | ------------ |
| Parent Control | cnt\-body\_1 |
