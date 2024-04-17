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

## Login

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

| Property      | Value                            |
| ------------- | -------------------------------- |
| Child Control | 8c98994518b575bfd8c949e91d20548b |
| Child Control | Image15                          |
| Child Control | msft\_Label                      |
| Child Control | username                         |
| Child Control | msft\_Label\_1                   |
| Child Control | password                         |
| Child Control | Mostrar                          |
| Child Control | View                             |
| Child Control | Button2                          |
| Child Control | msft\_Button                     |
| Child Control | Tac\_Icon                        |

## 8c98994518b575bfd8c949e91d20548b

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![image](resources/image.png) | Type: image |

### Behavior

| Property | Value                                                                                                                                           |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property        | Value                                                                                                                                                            |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| AccessibleLabel | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                     |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                     |
| Image           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">image270710<td style="background-color:#ffcccc; width:50%;">SampleImage</td></tr></table> |
| Tooltip         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                     |

### Design

| Property                    | Value                                                                                                                                                                       |
| --------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ApplyEXIFOrientation        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                              |
| AutoDisableOnSelect         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                              |
| BorderStyle                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table> |
| BorderThickness             | 0                                                                                                                                                                           |
| CalculateOriginalDimensions | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                             |
| DisplayMode                 | DisplayMode.Edit                                                                                                                                                            |
| FlipHorizontal              | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                             |
| FlipVertical                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                             |
| FocusedBorderThickness      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;">2</td></tr></table>                                |
| Height                      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1136<td style="background-color:#ffcccc; width:50%;">100</td></tr></table>                           |
| ImagePosition               | ImagePosition.Fit                                                                                                                                                           |
| ImageRotation               | ImageRotation.None                                                                                                                                                          |
| maximumHeight               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">768<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                               |
| maximumWidth                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1366<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                              |
| minimumHeight               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| minimumWidth                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| PaddingBottom               | 0                                                                                                                                                                           |
| PaddingLeft                 | 0                                                                                                                                                                           |
| PaddingRight                | 0                                                                                                                                                                           |
| PaddingTop                  | 0                                                                                                                                                                           |
| RadiusBottomLeft            | 0                                                                                                                                                                           |
| RadiusBottomRight           | 0                                                                                                                                                                           |
| RadiusTopLeft               | 0                                                                                                                                                                           |
| RadiusTopRight              | 0                                                                                                                                                                           |
| TabIndex                    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">-1<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                |
| Transparency                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| Visible                     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                              |
| Width                       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">640<td style="background-color:#ffcccc; width:50%;">100</td></tr></table>                            |
| X                           | 0                                                                                                                                                                           |
| Y                           | 0                                                                                                                                                                           |
| ZIndex                      | 2                                                                                                                                                                           |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                                    |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>               |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table>            |
| DisabledFill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table></td></tr></table>            |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                          |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                         |
| HoverBorderColor    | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.BorderColor, 20%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>  |
| HoverFill           | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.Fill, 20%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>         |
| PressedBorderColor  | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.BorderColor, -20%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table> |
| PressedFill         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.Fill, -20%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>        |

### Child & Parent Controls

| Property       | Value |
| -------------- | ----- |
| Parent Control | Login |

## Button2

| Property                        | Value        |
| ------------------------------- | ------------ |
| ![button](resources/button.png) | Type: button |

### Behavior

| Property | Value                                                                                                                                                                |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Navigate(Recover_Password)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property | Value                                                                                                                                                                       |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Esqueceu a sua password"<td style="background-color:#ffcccc; width:50%;">"Button"</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                                                                    |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Align                  | Align.Center                                                                                                                                                                                                             |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table>                                              |
| BorderThickness        | 2                                                                                                                                                                                                                        |
| DisplayMode            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(IsBlank(Varusername),DisplayMode.Disabled,DisplayMode.Edit)<td style="background-color:#ffcccc; width:50%;">DisplayMode.Edit</td></tr></table> |
| FocusedBorderThickness | 4                                                                                                                                                                                                                        |
| Font                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Font.'Segoe UI'<td style="background-color:#ffcccc; width:50%;">Font.'Open Sans'</td></tr></table>                                                |
| FontWeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">FontWeight.Bold<td style="background-color:#ffcccc; width:50%;">FontWeight.Semibold</td></tr></table>                                             |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">44<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                                                                           |
| Italic                 | false                                                                                                                                                                                                                    |
| RadiusBottomLeft       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">10</td></tr></table>                                                                            |
| RadiusBottomRight      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">10</td></tr></table>                                                                            |
| RadiusTopLeft          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">10</td></tr></table>                                                                            |
| RadiusTopRight         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">10</td></tr></table>                                                                            |
| Size                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;">15</td></tr></table>                                                                           |
| Strikethrough          | false                                                                                                                                                                                                                    |
| Underline              | false                                                                                                                                                                                                                    |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                                                                     |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">280<td style="background-color:#ffcccc; width:50%;">160</td></tr></table>                                                                         |
| X                      | 320                                                                                                                                                                                                                      |
| Y                      | 761                                                                                                                                                                                                                      |
| ZIndex                 | 9                                                                                                                                                                                                                        |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                                            |
| ------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.Fill, -15%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>                |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(20, 52, 84, 1)</td></tr><tr><td style="background-color:#143454"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td></tr></table>                 |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table>                    |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table>                                                                                                                                                                                                                                                                                                            |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table>                                                                                                                                                                                                                                                                                                            |
| Fill                | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 10, 0, 0.01)</td></tr><tr><td style="background-color:#000A00"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table></td></tr></table>                  |
| FocusedBorderColor  | ColorFade(Self.Fill, \-75%)                                                                                                                                                                                                                                                                                                                                                                                                      |
| HoverBorderColor    | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.BorderColor, 20%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>          |
| HoverColor          | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 134, 208, 1)</td></tr><tr><td style="background-color:#0086D0"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td></tr></table>                |
| HoverFill           | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 120, 212, 0)</td></tr><tr><td style="background-color:#0078D4"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(RGBA(56, 96, 178, 1), -20%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table> |
| PressedBorderColor  | ColorFade(RGBA(0, 120, 212, 1), \-50%)                                                                                                                                                                                                                                                                                                                                                                                           |
| PressedColor        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.Fill</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>                           |
| PressedFill         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 120, 212, 0)</td></tr><tr><td style="background-color:#0078D4"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.Color</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>                            |

### Child & Parent Controls

| Property       | Value |
| -------------- | ----- |
| Parent Control | Login |

## Image15

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![image](resources/image.png) | Type: image |

### Data

| Property | Value                                                                                                                                                     |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Image    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">logo<td style="background-color:#ffcccc; width:50%;">SampleImage</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                       |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table> |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                            |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;">2</td></tr></table>                                |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">320<td style="background-color:#ffcccc; width:50%;">100</td></tr></table>                            |
| ImagePosition          | ImagePosition.Fit                                                                                                                                                           |
| ImageRotation          | ImageRotation.None                                                                                                                                                          |
| PaddingBottom          | 0                                                                                                                                                                           |
| PaddingLeft            | 0                                                                                                                                                                           |
| PaddingRight           | 0                                                                                                                                                                           |
| PaddingTop             | 0                                                                                                                                                                           |
| RadiusBottomLeft       | 0                                                                                                                                                                           |
| RadiusBottomRight      | 0                                                                                                                                                                           |
| RadiusTopLeft          | 0                                                                                                                                                                           |
| RadiusTopRight         | 0                                                                                                                                                                           |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">320<td style="background-color:#ffcccc; width:50%;">100</td></tr></table>                            |
| X                      | 160                                                                                                                                                                         |
| Y                      | 84                                                                                                                                                                          |
| ZIndex                 | 10                                                                                                                                                                          |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                                    |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>               |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table>            |
| DisabledFill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table></td></tr></table>            |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                          |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                         |
| HoverBorderColor    | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.BorderColor, 20%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>  |
| HoverFill           | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.Fill, 20%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>         |
| PressedBorderColor  | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.BorderColor, -20%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table> |
| PressedFill         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.Fill, -20%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>        |

### Child & Parent Controls

| Property       | Value |
| -------------- | ----- |
| Parent Control | Login |

## Mostrar

| Property                        | Value        |
| ------------------------------- | ------------ |
| ![button](resources/button.png) | Type: button |

### Behavior

| Property | Value |
| -------- | ----- |
| OnSelect |       |

### Data

| Property | Value                                                                                                                                                |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;">"Button"</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                       |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align                  | Align.Center                                                                                                                                                                |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table> |
| BorderThickness        | 2                                                                                                                                                                           |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                            |
| FocusedBorderThickness | 4                                                                                                                                                                           |
| Font                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Font.'Segoe UI'<td style="background-color:#ffcccc; width:50%;">Font.'Open Sans'</td></tr></table>   |
| FontWeight             | FontWeight.Semibold                                                                                                                                                         |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">48<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                              |
| Italic                 | false                                                                                                                                                                       |
| RadiusBottomLeft       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">10</td></tr></table>                               |
| RadiusBottomRight      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">10</td></tr></table>                               |
| RadiusTopLeft          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">10</td></tr></table>                               |
| RadiusTopRight         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">10</td></tr></table>                               |
| Size                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">24<td style="background-color:#ffcccc; width:50%;">15</td></tr></table>                              |
| Strikethrough          | false                                                                                                                                                                       |
| Underline              | false                                                                                                                                                                       |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                        |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">69<td style="background-color:#ffcccc; width:50%;">160</td></tr></table>                             |
| X                      | 517                                                                                                                                                                         |
| Y                      | 690                                                                                                                                                                         |
| ZIndex                 | 12                                                                                                                                                                          |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                                            |
| ------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.Fill, -15%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>                |
| Color               | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table>                                                                                                                                                                                                                                                                                                            |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table>                    |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table>                                                                                                                                                                                                                                                                                                            |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table>                                                                                                                                                                                                                                                                                                            |
| Fill                | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table></td></tr></table>                      |
| FocusedBorderColor  | ColorFade(Self.Fill, \-75%)                                                                                                                                                                                                                                                                                                                                                                                                      |
| HoverBorderColor    | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.BorderColor, 20%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>          |
| HoverColor          | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table>                                                                                                                                                                                                                                                                                                            |
| HoverFill           | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 120, 212, 0)</td></tr><tr><td style="background-color:#0078D4"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(RGBA(56, 96, 178, 1), -20%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table> |
| PressedBorderColor  | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 120, 212, 0)</td></tr><tr><td style="background-color:#0078D4"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.Fill</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>                             |
| PressedColor        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.Fill</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>                           |
| PressedFill         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 120, 212, 0)</td></tr><tr><td style="background-color:#0078D4"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.Color</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>                            |

### Child & Parent Controls

| Property       | Value |
| -------------- | ----- |
| Parent Control | Login |

## msft\_Button

| Property                        | Value        |
| ------------------------------- | ------------ |
| ![button](resources/button.png) | Type: button |

### Behavior

| Property | Value                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(And(IsBlank(username.Text),IsBlank(password.Text)),false, If( //Or(username.Text = LookUp(UsersInfo, Username = username.Text).username,username.Text = LookUp(UsersInfo, Email = Username.Text).Email) - se tivessemos coluna email username.Text = LookUp(UsersInfo, Username = username.Text).Username && password.Text = LookUp(UsersInfo, Username = username.Text).Passwords, Navigate(Home,ScreenTransition.Fade,{Varusername: username.Text}), Set(Varusername,username.Text) ); Reset(username)&Reset(password))<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property        | Value                                                                                                                                                              |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| Text            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Iniciar Sessão"<td style="background-color:#ffcccc; width:50%;">"Button"</td></tr></table> |
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
| X                      | 149                                                                                                                                                                             |
| Y                      | 849                                                                                                                                                                             |
| ZIndex                 | 3                                                                                                                                                                               |

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

| Property       | Value |
| -------------- | ----- |
| Parent Control | Login |

## msft\_Label

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Behavior

| Property | Value                                                                                                                                           |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property        | Value                                                                                                                                                                |
| --------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Live            | Live.Off                                                                                                                                                             |
| Role            | TextRole.Default                                                                                                                                                     |
| Text            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Nome de utilizador"<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |
| Tooltip         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |

### Design

| Property               | Value                                                                                                                                                                       |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align                  | Align.Left                                                                                                                                                                  |
| AutoHeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                             |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table> |
| BorderThickness        | 0                                                                                                                                                                           |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                            |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                |
| Font                   | Font.'Open Sans'                                                                                                                                                            |
| FontWeight             | FontWeight.Normal                                                                                                                                                           |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">36<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                              |
| IsErrorMessage         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                             |
| Italic                 | false                                                                                                                                                                       |
| LineHeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1.207031<td style="background-color:#ffcccc; width:50%;">1.2</td></tr></table>                       |
| maximumHeight          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">7680<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                              |
| maximumWidth           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1366<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                              |
| minimumHeight          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| minimumWidth           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| Overflow               | Overflow.Hidden                                                                                                                                                             |
| PaddingBottom          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">15<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                               |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                |
| PaddingRight           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                |
| PaddingTop             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">15<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                               |
| Size                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">22.5<td style="background-color:#ffcccc; width:50%;">13</td></tr></table>                            |
| Strikethrough          | false                                                                                                                                                                       |
| TabIndex               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">-1<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                |
| Underline              | false                                                                                                                                                                       |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                        |
| Visible                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                              |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">270<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>                            |
| Wrap                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                              |
| X                      | 40                                                                                                                                                                          |
| Y                      | 474                                                                                                                                                                         |
| ZIndex                 | 7                                                                                                                                                                           |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                      |
| ------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table> |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(20, 52, 84, 1)</td></tr><tr><td style="background-color:#143454"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table> |
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

| Property       | Value |
| -------------- | ----- |
| Parent Control | Login |

## msft\_Label\_1

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Behavior

| Property | Value                                                                                                                                           |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property        | Value                                                                                                                                                      |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| Live            | Live.Off                                                                                                                                                   |
| Role            | TextRole.Default                                                                                                                                           |
| Text            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Password"<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |
| Tooltip         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |

### Design

| Property               | Value                                                                                                                                                                       |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align                  | Align.Left                                                                                                                                                                  |
| AutoHeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                             |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table> |
| BorderThickness        | 0                                                                                                                                                                           |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                            |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                |
| Font                   | Font.'Open Sans'                                                                                                                                                            |
| FontWeight             | FontWeight.Normal                                                                                                                                                           |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">36<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                              |
| IsErrorMessage         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                             |
| Italic                 | false                                                                                                                                                                       |
| LineHeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1.207031<td style="background-color:#ffcccc; width:50%;">1.2</td></tr></table>                       |
| maximumHeight          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">7680<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                              |
| maximumWidth           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1366<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                              |
| minimumHeight          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| minimumWidth           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| Overflow               | Overflow.Hidden                                                                                                                                                             |
| PaddingBottom          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">15<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                               |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                |
| PaddingRight           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                |
| PaddingTop             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">15<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                               |
| Size                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">22.5<td style="background-color:#ffcccc; width:50%;">13</td></tr></table>                            |
| Strikethrough          | false                                                                                                                                                                       |
| TabIndex               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">-1<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                |
| Underline              | false                                                                                                                                                                       |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                        |
| Visible                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                              |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">140<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>                            |
| Wrap                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                              |
| X                      | 40                                                                                                                                                                          |
| Y                      | 630                                                                                                                                                                         |
| ZIndex                 | 8                                                                                                                                                                           |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                      |
| ------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table> |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(20, 52, 84, 1)</td></tr><tr><td style="background-color:#143454"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table> |
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

| Property       | Value |
| -------------- | ----- |
| Parent Control | Login |

## password

| Property                    | Value      |
| --------------------------- | ---------- |
| ![text](resources/text.png) | Type: text |

### Behavior

| Property | Value                                                                                                                                           |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| OnChange | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property        | Value                                                                                                                                                           |
| --------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| AccessibleLabel | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| Default         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;"><td style="background-color:#ffcccc; width:50%;">"Text input"</td></tr></table>          |
| DelayOutput     | false                                                                                                                                                           |
| HintText        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Insira password"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| MaxLength       |                                                                                                                                                                 |
| Reset           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Tooltip         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Introduzir password"<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                                                                  |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align                  | Align.Left                                                                                                                                                                                                             |
| BorderStyle            | BorderStyle.Solid                                                                                                                                                                                                      |
| BorderThickness        | 2                                                                                                                                                                                                                      |
| Clear                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                        |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                                                                       |
| EnableSpellCheck       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                        |
| FocusedBorderThickness | 4                                                                                                                                                                                                                      |
| Font                   | Font.'Open Sans'                                                                                                                                                                                                       |
| FontWeight             | FontWeight.Normal                                                                                                                                                                                                      |
| Format                 | TextFormat.Text                                                                                                                                                                                                        |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">70<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                                                                         |
| Italic                 | false                                                                                                                                                                                                                  |
| LineHeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1.132813<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                     |
| maximumHeight          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">768<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                          |
| maximumWidth           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1366<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                         |
| minimumHeight          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                           |
| minimumWidth           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                           |
| Mode                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Mostrar.Pressed,TextMode.SingleLine,TextMode.Password)<td style="background-color:#ffcccc; width:50%;">TextMode.SingleLine</td></tr></table> |
| PaddingBottom          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">15<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                           |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                           |
| PaddingRight           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                           |
| PaddingTop             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">15<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                           |
| RadiusBottomLeft       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">80<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                                                          |
| RadiusBottomRight      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">80<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                                                          |
| RadiusTopLeft          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">80<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                                                          |
| RadiusTopRight         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">80<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                                                          |
| Size                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">18<td style="background-color:#ffcccc; width:50%;">13</td></tr></table>                                                                         |
| Strikethrough          | false                                                                                                                                                                                                                  |
| TabIndex               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                            |
| Underline              | false                                                                                                                                                                                                                  |
| VirtualKeyboardMode    | VirtualKeyboardMode.Auto                                                                                                                                                                                               |
| Visible                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                         |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">560<td style="background-color:#ffcccc; width:50%;">320</td></tr></table>                                                                       |
| X                      | 40                                                                                                                                                                                                                     |
| Y                      | 679                                                                                                                                                                                                                    |
| ZIndex                 | 5                                                                                                                                                                                                                      |

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

| Property       | Value |
| -------------- | ----- |
| Parent Control | Login |

## Tac\_Icon

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![image](resources/image.png) | Type: image |

### Behavior

| Property | Value                                                                                                                                           |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property        | Value                                                                                                                                                            |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| AccessibleLabel | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                     |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                     |
| Image           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">image270712<td style="background-color:#ffcccc; width:50%;">SampleImage</td></tr></table> |
| Tooltip         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                     |

### Design

| Property                    | Value                                                                                                                                                                       |
| --------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ApplyEXIFOrientation        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                              |
| AutoDisableOnSelect         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                              |
| BorderStyle                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table> |
| BorderThickness             | 0                                                                                                                                                                           |
| CalculateOriginalDimensions | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                             |
| DisplayMode                 | DisplayMode.Edit                                                                                                                                                            |
| FlipHorizontal              | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                             |
| FlipVertical                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                             |
| FocusedBorderThickness      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;">2</td></tr></table>                                |
| Height                      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">98<td style="background-color:#ffcccc; width:50%;">100</td></tr></table>                             |
| ImagePosition               | ImagePosition.Fit                                                                                                                                                           |
| ImageRotation               | ImageRotation.None                                                                                                                                                          |
| maximumHeight               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">768<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                               |
| maximumWidth                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1366<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                              |
| minimumHeight               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| minimumWidth                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| PaddingBottom               | 0                                                                                                                                                                           |
| PaddingLeft                 | 0                                                                                                                                                                           |
| PaddingRight                | 0                                                                                                                                                                           |
| PaddingTop                  | 0                                                                                                                                                                           |
| RadiusBottomLeft            | 0                                                                                                                                                                           |
| RadiusBottomRight           | 0                                                                                                                                                                           |
| RadiusTopLeft               | 0                                                                                                                                                                           |
| RadiusTopRight              | 0                                                                                                                                                                           |
| TabIndex                    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">-1<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                |
| Transparency                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| Visible                     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                              |
| Width                       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">268<td style="background-color:#ffcccc; width:50%;">100</td></tr></table>                            |
| X                           | 186                                                                                                                                                                         |
| Y                           | 968                                                                                                                                                                         |
| ZIndex                      | 4                                                                                                                                                                           |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                                    |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>               |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table>            |
| DisabledFill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table></td></tr></table>            |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                          |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                         |
| HoverBorderColor    | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.BorderColor, 20%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>  |
| HoverFill           | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.Fill, 20%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>         |
| PressedBorderColor  | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.BorderColor, -20%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table> |
| PressedFill         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.Fill, -20%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>        |

### Child & Parent Controls

| Property       | Value |
| -------------- | ----- |
| Parent Control | Login |

## username

| Property                    | Value      |
| --------------------------- | ---------- |
| ![text](resources/text.png) | Type: text |

### Behavior

| Property | Value                                                                                                                                           |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| OnChange | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property        | Value                                                                                                                                                                    |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| AccessibleLabel | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                             |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                             |
| Default         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;"><td style="background-color:#ffcccc; width:50%;">"Text input"</td></tr></table>                   |
| DelayOutput     | false                                                                                                                                                                    |
| HintText        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Insira nome de utilizador"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| MaxLength       |                                                                                                                                                                          |
| Reset           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| Tooltip         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Introduza nome de utilizador"<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property               | Value                                                                                                                                              |
| ---------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align                  | Align.Left                                                                                                                                         |
| BorderStyle            | BorderStyle.Solid                                                                                                                                  |
| BorderThickness        | 2                                                                                                                                                  |
| Clear                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| DisplayMode            | DisplayMode.Edit                                                                                                                                   |
| EnableSpellCheck       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| FocusedBorderThickness | 4                                                                                                                                                  |
| Font                   | Font.'Open Sans'                                                                                                                                   |
| FontWeight             | FontWeight.Normal                                                                                                                                  |
| Format                 | TextFormat.Text                                                                                                                                    |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">70<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>     |
| Italic                 | false                                                                                                                                              |
| LineHeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1.132813<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| maximumHeight          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">768<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| maximumWidth           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1366<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| minimumHeight          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |
| minimumWidth           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |
| Mode                   | TextMode.SingleLine                                                                                                                                |
| PaddingBottom          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">15<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |
| PaddingRight           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |
| PaddingTop             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">15<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |
| RadiusBottomLeft       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">80<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>      |
| RadiusBottomRight      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">80<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>      |
| RadiusTopLeft          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">80<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>      |
| RadiusTopRight         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">80<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>      |
| Size                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">18<td style="background-color:#ffcccc; width:50%;">13</td></tr></table>     |
| Strikethrough          | false                                                                                                                                              |
| TabIndex               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| Underline              | false                                                                                                                                              |
| VirtualKeyboardMode    | VirtualKeyboardMode.Auto                                                                                                                           |
| Visible                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">560<td style="background-color:#ffcccc; width:50%;">320</td></tr></table>   |
| X                      | 40                                                                                                                                                 |
| Y                      | 523                                                                                                                                                |
| ZIndex                 | 6                                                                                                                                                  |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | If( IsBlank(username.Text), Color.DarkBlue, If( LookUp( UsersInfo, Username \= username.Text, Username ) \= username.Text, Color.Green, Color.DarkRed ) )                                                                                                                                                                                                                                                           |
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

| Property       | Value |
| -------------- | ----- |
| Parent Control | Login |

## View

| Property                    | Value      |
| --------------------------- | ---------- |
| ![icon](resources/icon.png) | Type: icon |

### Behavior

| Property | Value |
| -------- | ----- |
| OnSelect |       |

### Design

| Property               | Value                                                                                                                                                       |
| ---------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| DisplayMode            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">48<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Icon                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Icon.View<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">40<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| X                      | 531                                                                                                                                                         |
| Y                      | 690                                                                                                                                                         |
| ZIndex                 | 11                                                                                                                                                          |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                      |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(29, 157, 255, 1)</td></tr><tr><td style="background-color:#1D9DFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>  |
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

| Property       | Value |
| -------------- | ----- |
| Parent Control | Login |
