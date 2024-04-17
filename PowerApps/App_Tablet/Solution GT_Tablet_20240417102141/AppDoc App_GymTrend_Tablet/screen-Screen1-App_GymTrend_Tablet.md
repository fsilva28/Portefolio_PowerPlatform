# Power App Documentation \- App\_GymTrend\_Tablet

| Property                   | Value                     |
| -------------------------- | ------------------------- |
| App Name                   | App\_GymTrend\_Tablet     |
| Documentation generated at | 17 de abril de 2024 11:22 |

- [Overview](index-App_GymTrend_Tablet.md)
- [App Details](appdetails-App_GymTrend_Tablet.md)
- [Variables](variables-App_GymTrend_Tablet.md)
- [DataSources](datasources-App_GymTrend_Tablet.md)
- [Resources](resources-App_GymTrend_Tablet.md)
- [Controls](controls-App_GymTrend_Tablet.md)

## Screen1

| Property                        | Value        |
| ------------------------------- | ------------ |
| ![screen](resources/screen.png) | Type: screen |

### Design

| Property            | Value                                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------- |
| Height              | Max(App.Height, App.MinScreenHeight)                                                                                |
| ImagePosition       | ImagePosition.Fit                                                                                                   |
| LoadingSpinner      | LoadingSpinner.None                                                                                                 |
| LoadingSpinnerColor | <table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table> |
| Orientation         | If(Self.Width \< Self.Height, Layout.Vertical, Layout.Horizontal)                                                   |
| Size                | 1 + CountRows(App.SizeBreakpoints) \- CountIf(App.SizeBreakpoints, Value \>\= Self.Width)                           |
| Width               | Max(App.Width, App.MinScreenWidth)                                                                                  |

### Color Properties

| Property | Value       |
| -------- | ----------- |
| Fill     | Color.White |

### Child & Parent Controls

| Property      | Value    |
| ------------- | -------- |
| Child Control | Camera1  |
| Child Control | Gallery2 |
| Child Control | Icon3    |

## Camera1

| Property                        | Value        |
| ------------------------------- | ------------ |
| ![camera](resources/camera.png) | Type: camera |

### Behavior

| Property | Value                                                                                                                                           |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property    | Value                                                                                                                                         |
| ----------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle | BorderStyle.Solid                                                                                                                             |
| Camera      | 0                                                                                                                                             |
| DisplayMode | DisplayMode.Edit                                                                                                                              |
| Height      | 300                                                                                                                                           |
| StreamRate  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width       | 400                                                                                                                                           |
| X           | 40                                                                                                                                            |
| Y           | 40                                                                                                                                            |
| ZIndex      | 1                                                                                                                                             |

### Color Properties

| Property           | Value                                                                                                              |
| ------------------ | ------------------------------------------------------------------------------------------------------------------ |
| BorderColor        | <table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table> |
| FocusedBorderColor | Self.BorderColor                                                                                                   |

### Child & Parent Controls

| Property       | Value   |
| -------------- | ------- |
| Parent Control | Screen1 |

## Gallery2

| Property                          | Value         |
| --------------------------------- | ------------- |
| ![gallery](resources/gallery.png) | Type: gallery |

### Data

| Property  | Value                                                                                                                                                              |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Items     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Fotos<td style="background-color:#ffcccc; width:50%;">CustomGallerySample</td></tr></table> |
| WrapCount | 1                                                                                                                                                                  |

### Design

| Property            | Value                                                                                                                                                                                                                                                          |
| ------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle         | BorderStyle.Solid                                                                                                                                                                                                                                              |
| DelayItemLoading    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                                 |
| DisplayMode         | DisplayMode.Edit                                                                                                                                                                                                                                               |
| Height              | 575                                                                                                                                                                                                                                                            |
| Layout              | Layout.Vertical                                                                                                                                                                                                                                                |
| LoadingSpinner      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LoadingSpinner.Data<td style="background-color:#ffcccc; width:50%;">LoadingSpinner.None</td></tr></table>                                                                               |
| LoadingSpinnerColor | Self.BorderColor                                                                                                                                                                                                                                               |
| TemplatePadding     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">5<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                                                                                                   |
| TemplateSize        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Self.Layout = Layout.Horizontal, Min(280, Self.Width - 60), Min(280, Self.Height - 60))<td style="background-color:#ffcccc; width:50%;">Min(160, Self.Height - 60)</td></tr></table> |
| Transition          | Transition.None                                                                                                                                                                                                                                                |
| Width               | 640                                                                                                                                                                                                                                                            |
| X                   | 701                                                                                                                                                                                                                                                            |
| Y                   | 40                                                                                                                                                                                                                                                             |
| ZIndex              | 3                                                                                                                                                                                                                                                              |

### Color Properties

| Property            | Value                                                                                                              |
| ------------------- | ------------------------------------------------------------------------------------------------------------------ |
| BorderColor         | <table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table> |
| DisabledBorderColor | Self.BorderColor                                                                                                   |
| DisabledFill        | Self.Fill                                                                                                          |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>    |
| FocusedBorderColor  | Self.BorderColor                                                                                                   |
| HoverBorderColor    | Self.BorderColor                                                                                                   |
| HoverFill           | Self.Fill                                                                                                          |
| PressedBorderColor  | Self.BorderColor                                                                                                   |
| PressedFill         | Self.Fill                                                                                                          |

### Child & Parent Controls

| Property       | Value            |
| -------------- | ---------------- |
| Child Control  | galleryTemplate2 |
| Child Control  | Image3           |
| Child Control  | Icon4            |
| Parent Control | Screen1          |

## galleryTemplate2

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
| Parent Control | Gallery2 |

## Icon3

| Property                    | Value      |
| --------------------------- | ---------- |
| ![icon](resources/icon.png) | Type: icon |

### Behavior

| Property | Value                                                                                                                                                                          |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Collect(Fotos,{foto:Camera1.Stream})<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property               | Value                                                                                                                                                       |
| ---------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| DisplayMode            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">64<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Icon                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Icon.AddDocument<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">64<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| X                      | 188                                                                                                                                                         |
| Y                      | 392                                                                                                                                                         |
| ZIndex                 | 2                                                                                                                                                           |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                      |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>    |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>    |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| DisabledFill        | Self.Fill                                                                                                                                                                                                                                                                                                                                  |
| Fill                | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                           |
| HoverBorderColor    | ColorFade(Self.BorderColor, 20%)                                                                                                                                                                                                                                                                                                           |
| HoverColor          | ColorFade(Self.Color, 20%)                                                                                                                                                                                                                                                                                                                 |
| HoverFill           | Self.Fill                                                                                                                                                                                                                                                                                                                                  |
| PressedBorderColor  | ColorFade(Self.BorderColor, \-20%)                                                                                                                                                                                                                                                                                                         |
| PressedColor        | ColorFade(Self.Color, \-20%)                                                                                                                                                                                                                                                                                                               |
| PressedFill         | Self.Fill                                                                                                                                                                                                                                                                                                                                  |

### Child & Parent Controls

| Property       | Value   |
| -------------- | ------- |
| Parent Control | Screen1 |

## Icon4

| Property                    | Value      |
| --------------------------- | ---------- |
| ![icon](resources/icon.png) | Type: icon |

### Behavior

| Property | Value                                                                                                                                                            |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Remove(Fotos,ThisItem)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property               | Value                                                                                                                                                       |
| ---------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| DisplayMode            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">64<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Icon                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Icon.Alarm<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">64<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| X                      | 28                                                                                                                                                          |
| Y                      | 152                                                                                                                                                         |
| ZIndex                 | 2                                                                                                                                                           |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                      |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>    |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>    |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| DisabledFill        | Self.Fill                                                                                                                                                                                                                                                                                                                                  |
| Fill                | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                           |
| HoverBorderColor    | ColorFade(Self.BorderColor, 20%)                                                                                                                                                                                                                                                                                                           |
| HoverColor          | ColorFade(Self.Color, 20%)                                                                                                                                                                                                                                                                                                                 |
| HoverFill           | Self.Fill                                                                                                                                                                                                                                                                                                                                  |
| PressedBorderColor  | ColorFade(Self.BorderColor, \-20%)                                                                                                                                                                                                                                                                                                         |
| PressedColor        | ColorFade(Self.Color, \-20%)                                                                                                                                                                                                                                                                                                               |
| PressedFill         | Self.Fill                                                                                                                                                                                                                                                                                                                                  |

### Child & Parent Controls

| Property       | Value    |
| -------------- | -------- |
| Parent Control | Gallery2 |

## Image3

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![image](resources/image.png) | Type: image |

### Behavior

| Property | Value                                                                                                                                                    |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Select(Parent)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property | Value                                                                                                                                                              |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Image    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.foto<td style="background-color:#ffcccc; width:50%;">SampleImage</td></tr></table> |

### Design

| Property               | Value              |
| ---------------------- | ------------------ |
| BorderStyle            | BorderStyle.Solid  |
| BorderThickness        | 0                  |
| DisplayMode            | DisplayMode.Edit   |
| FocusedBorderThickness | 2                  |
| Height                 | 100                |
| ImagePosition          | ImagePosition.Fit  |
| ImageRotation          | ImageRotation.None |
| PaddingBottom          | 0                  |
| PaddingLeft            | 0                  |
| PaddingRight           | 0                  |
| PaddingTop             | 0                  |
| RadiusBottomLeft       | 0                  |
| RadiusBottomRight      | 0                  |
| RadiusTopLeft          | 0                  |
| RadiusTopRight         | 0                  |
| Width                  | 100                |
| X                      | 40                 |
| Y                      | 40                 |
| ZIndex                 | 1                  |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table>    |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| FocusedBorderColor  | Self.BorderColor                                                                                                      |
| HoverBorderColor    | ColorFade(Self.BorderColor, 20%)                                                                                      |
| HoverFill           | ColorFade(Self.Fill, 20%)                                                                                             |
| PressedBorderColor  | ColorFade(Self.BorderColor, \-20%)                                                                                    |
| PressedFill         | ColorFade(Self.Fill, \-20%)                                                                                           |

### Child & Parent Controls

| Property       | Value    |
| -------------- | -------- |
| Parent Control | Gallery2 |
