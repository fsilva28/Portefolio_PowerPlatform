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

## User Management

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

| Property      | Value        |
| ------------- | ------------ |
| Child Control | cnt\_main\_8 |

## AddPicture1\_1

| Property                            | Value          |
| ----------------------------------- | -------------- |
| ![addMedia](resources/addMedia.png) | Type: addMedia |

### Design

| Property               | Value                                                                                                                                            |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| Align                  | Align.Center                                                                                                                                     |
| BorderStyle            | BorderStyle.Solid                                                                                                                                |
| BorderThickness        | 0                                                                                                                                                |
| DisplayMode            | DisplayMode.Edit                                                                                                                                 |
| FocusedBorderThickness | 2                                                                                                                                                |
| Font                   | Font.'Open Sans'                                                                                                                                 |
| FontWeight             | FontWeight.Semibold                                                                                                                              |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">194<td style="background-color:#ffcccc; width:50%;">246</td></tr></table> |
| Italic                 | false                                                                                                                                            |
| Padding                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Size                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">11<td style="background-color:#ffcccc; width:50%;">25</td></tr></table>   |
| Strikethrough          | false                                                                                                                                            |
| Underline              | false                                                                                                                                            |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                             |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">259<td style="background-color:#ffcccc; width:50%;">328</td></tr></table> |
| X                      | 87                                                                                                                                               |
| Y                      | 10                                                                                                                                               |
| ZIndex                 | 3                                                                                                                                                |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table>    |
| Color               | <table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table>    |
| DisabledColor       | <table border="0"><tr><td>RGBA(186, 186, 186, 1)</td></tr><tr><td style="background-color:#BABABA"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(119, 119, 119, 1)</td></tr><tr><td style="background-color:#777777"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| FocusedBorderColor  | Self.BorderColor                                                                                                      |
| HoverBorderColor    | ColorFade(Self.BorderColor, 20%)                                                                                      |
| HoverColor          | Self.Color                                                                                                            |
| HoverFill           | ColorFade(Self.Fill, 20%)                                                                                             |
| PressedBorderColor  | ColorFade(Self.BorderColor, \-20%)                                                                                    |
| PressedColor        | Self.Color                                                                                                            |
| PressedFill         | ColorFade(Self.Fill, \-20%)                                                                                           |

### Child & Parent Controls

| Property       | Value                |
| -------------- | -------------------- |
| Parent Control | Imagem\_DataCard1\_1 |

## BackIconButton1

| Property                    | Value      |
| --------------------------- | ---------- |
| ![icon](resources/icon.png) | Type: icon |

### Behavior

| Property | Value                                                                                                                                                                            |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">UpdateContext({ itemSelected: false })<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                                                                               |
| ---------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                         |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                         |
| DisplayMode            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                          |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                         |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">50<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                        |
| Icon                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Icon.ChevronLeft<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                          |
| PaddingBottom          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">12<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                        |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">12<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                        |
| PaddingRight           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">12<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                        |
| PaddingTop             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">12<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                        |
| TabIndex               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                         |
| Visible                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(BodyContainer1.Width = ScreenSize.Small, And(!editMode, !newMode, !deleteMode), false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">50<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                        |
| X                      | 0                                                                                                                                                                                                                                   |
| Y                      | 0                                                                                                                                                                                                                                   |
| ZIndex                 | 16                                                                                                                                                                                                                                  |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                      |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 120, 212, 1)</td></tr><tr><td style="background-color:#0078D4"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>   |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(245, 245, 245, 1)</td></tr><tr><td style="background-color:#F5F5F5"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(225, 223, 221, 1)</td></tr><tr><td style="background-color:#E1DFDD"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| Fill                | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                           |
| HoverBorderColor    | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| HoverColor          | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(16, 110, 190, 1)</td></tr><tr><td style="background-color:#106EBE"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>  |
| HoverFill           | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| PressedBorderColor  | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| PressedColor        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(16, 110, 190, 1)</td></tr><tr><td style="background-color:#106EBE"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>  |
| PressedFill         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |

### Child & Parent Controls

| Property       | Value                          |
| -------------- | ------------------------------ |
| Parent Control | SelectedRecordHeaderContainer1 |

## Body1

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Behavior

| Property | Value                                                                                                                                                    |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Select(Parent)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property | Value                                                                                                                                                              |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Live     | Live.Off                                                                                                                                                           |
| Role     | TextRole.Default                                                                                                                                                   |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.Passwords<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |
| Tooltip  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Password"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |

### Design

| Property      | Value                                                                                                                                                                                                                      |
| ------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align         | Align.Left                                                                                                                                                                                                                 |
| BorderStyle   | BorderStyle.Solid                                                                                                                                                                                                          |
| DisplayMode   | DisplayMode.Edit                                                                                                                                                                                                           |
| Font          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Font.'Segoe UI'<td style="background-color:#ffcccc; width:50%;">Font.'Open Sans'</td></tr></table>                                                  |
| FontWeight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(ThisItem.IsSelected, FontWeight.Semibold, FontWeight.Normal)<td style="background-color:#ffcccc; width:50%;">FontWeight.Normal</td></tr></table> |
| Height        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Self.Size * 1.8<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                                                                |
| Overflow      | Overflow.Hidden                                                                                                                                                                                                            |
| PaddingBottom | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                                                               |
| PaddingLeft   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">12<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                                                              |
| PaddingRight  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                                                               |
| PaddingTop    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                                                               |
| Size          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">12<td style="background-color:#ffcccc; width:50%;">13</td></tr></table>                                                                             |
| TabIndex      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">-1<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                               |
| VerticalAlign | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">VerticalAlign.Top<td style="background-color:#ffcccc; width:50%;">VerticalAlign.Middle</td></tr></table>                                            |
| Width         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Title1_1.Width<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>                                                                |
| X             | Title1\_1.X                                                                                                                                                                                                                |
| Y             | Subtitle1\_1.Y + Subtitle1\_1.Height                                                                                                                                                                                       |
| ZIndex        | 3                                                                                                                                                                                                                          |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>          |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(96, 94, 92, 1)</td></tr><tr><td style="background-color:#605E5C"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>          |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table>                                                                                                                                                                                                                                                                                                  |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(161, 159, 157, 1)</td></tr><tr><td style="background-color:#A19F9D"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                     |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                     |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverBorderColor    | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverColor          | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                          |
| HoverFill           | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                           |
| PressedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| PressedColor        | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                          |
| PressedFill         | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                           |

### Child & Parent Controls

| Property       | Value           |
| -------------- | --------------- |
| Parent Control | RecordsGallery1 |

## BodyContainer1

| Property                                                                      | Value                               |
| ----------------------------------------------------------------------------- | ----------------------------------- |
| ![horizontalAutoLayoutContainer](resources/horizontalAutoLayoutContainer.png) | Type: horizontalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.None<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">200<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Horizontal<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| PaddingBottom        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| PaddingLeft          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| PaddingRight         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| PaddingTop           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">500<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| X                    | 0                                                                                                                                                                    |
| Y                    | 0                                                                                                                                                                    |
| ZIndex               | 4                                                                                                                                                                    |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value                         |
| -------------- | ----------------------------- |
| Child Control  | SidebarContainer1             |
| Child Control  | RightContainer1               |
| Child Control  | DeleteConfirmDialogContainer1 |
| Parent Control | ScreenContainer1              |

## CancelDeleteButton1

| Property                        | Value        |
| ------------------------------- | ------------ |
| ![button](resources/button.png) | Type: button |

### Behavior

| Property | Value                                                                                                                                                                                                 |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">UpdateContext({ deleteMode: false, deleteCancelled: true })<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property | Value                                                                                                                                                      |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Cancel"<td style="background-color:#ffcccc; width:50%;">"Button"</td></tr></table> |

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
| Height                 | 40                                                                                                                                                                          |
| Italic                 | false                                                                                                                                                                       |
| RadiusBottomLeft       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">10</td></tr></table>                               |
| RadiusBottomRight      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">10</td></tr></table>                               |
| RadiusTopLeft          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">10</td></tr></table>                               |
| RadiusTopRight         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">10</td></tr></table>                               |
| Size                   | 15                                                                                                                                                                          |
| Strikethrough          | false                                                                                                                                                                       |
| Underline              | false                                                                                                                                                                       |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                        |
| Width                  | 160                                                                                                                                                                         |
| X                      | 0                                                                                                                                                                           |
| Y                      | 0                                                                                                                                                                           |
| ZIndex                 | 27                                                                                                                                                                          |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                                             |
| ------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.Fill, -15%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>                 |
| Color               | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table>                                                                                                                                                                                                                                                                                                             |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table>                     |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(161, 159, 157, 1)</td></tr><tr><td style="background-color:#A19F9D"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table>               |
| DisabledFill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(242, 242, 241, 0)</td></tr><tr><td style="background-color:#F2F2F1"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table></td></tr></table>               |
| Fill                | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 120, 212, 1)</td></tr><tr><td style="background-color:#0078D4"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table></td></tr></table>                   |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                                  |
| HoverBorderColor    | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.BorderColor, 20%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>           |
| HoverColor          | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table>                                                                                                                                                                                                                                                                                                             |
| HoverFill           | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(16, 110, 190, 1)</td></tr><tr><td style="background-color:#106EBE"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(RGBA(56, 96, 178, 1), -20%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table> |
| PressedBorderColor  | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 69, 120, 1)</td></tr><tr><td style="background-color:#004578"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.Fill</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>                               |
| PressedColor        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.Fill</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>                            |
| PressedFill         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(16, 110, 190, 1)</td></tr><tr><td style="background-color:#106EBE"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.Color</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>                            |

### Child & Parent Controls

| Property       | Value                            |
| -------------- | -------------------------------- |
| Parent Control | ConfirmDeleteButtonBarContainer1 |

## cnt\_body\_rec\_4

| Property                                                                      | Value                               |
| ----------------------------------------------------------------------------- | ----------------------------------- |
| ![horizontalAutoLayoutContainer](resources/horizontalAutoLayoutContainer.png) | Type: horizontalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.Light<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">200<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Horizontal<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
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

| Property       | Value         |
| -------------- | ------------- |
| Child Control  | Container9\_4 |
| Child Control  | Container1    |
| Parent Control | cnt\_main\_8  |

## cnt\_footer\_8

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
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">cnt_header_8.Height/2<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
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
| ZIndex               | 4                                                                                                                                                                  |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | ColorValue("\#FC417B")                                                                                                                                                                                                                                                                                                               |

### Child & Parent Controls

| Property       | Value        |
| -------------- | ------------ |
| Child Control  | Footer\_9    |
| Parent Control | cnt\_main\_8 |

## cnt\_header\_8

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
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
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
| Child Control  | Header\_9    |
| Parent Control | cnt\_main\_8 |

## cnt\_main\_8

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
| X                    | 0                                                                                                                                                                    |
| Y                    | 0                                                                                                                                                                    |
| ZIndex               | 1                                                                                                                                                                    |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                      |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value             |
| -------------- | ----------------- |
| Child Control  | cnt\_header\_8    |
| Child Control  | cnt\_body\_rec\_4 |
| Child Control  | cnt\_footer\_8    |
| Parent Control | User Management   |

## Component1\_6

| Property                              | Value           |
| ------------------------------------- | --------------- |
| ![component](resources/component.png) | Type: component |

### Data

| Property    | Value                                                                                                                                                                                                                                                                                                                                                                                                                              |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Menu\_Items | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Table( { Page_Name: "Home", Screen: Home, Icon: Icon.Home }, { Page_Name: "Report", Screen: Report, Icon: Icon.Trending }, { Page_Name: "User Management", Screen: 'User Management', Icon: Icon.Person }, { Page_Name: "Gym Management", Screen: 'Gym Management', Icon: Icon.Tools } )<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Menu\_Width | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(VarMenuWidth=true,320,65)<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                                                                                                                                                                             |

### Design

| Property | Value                                                                                                                                                             |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Height   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| Width    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Component1_6.Menu_Width<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| X        | 0                                                                                                                                                                 |
| Y        | 0                                                                                                                                                                 |
| ZIndex   | 1                                                                                                                                                                 |

### Color Properties

| Property | Value                                                                                                                                                                                                                                                                                                                                        |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Fill     | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(146, 146, 146, 0.2)</td></tr><tr><td style="background-color:#929292"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value         |
| -------------- | ------------- |
| Parent Control | Container9\_4 |

## ConfirmDeleteButton1

| Property                        | Value        |
| ------------------------------- | ------------ |
| ![button](resources/button.png) | Type: button |

### Behavior

| Property | Value                                                                                                                                                                                                                                                                                                                                                                |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Remove([@Users_Info], selectedRecord); If(IsEmpty(Errors([@Users_Info], selectedRecord)), UpdateContext( { CurrentItem: First([@Users_Info]), itemSelected: false, editMode: false, newMode: false, deleteMode: false }));<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property | Value                                                                                                                                                      |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Delete"<td style="background-color:#ffcccc; width:50%;">"Button"</td></tr></table> |

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
| Height                 | 40                                                                                                                                                                          |
| Italic                 | false                                                                                                                                                                       |
| RadiusBottomLeft       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">10</td></tr></table>                               |
| RadiusBottomRight      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">10</td></tr></table>                               |
| RadiusTopLeft          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">10</td></tr></table>                               |
| RadiusTopRight         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">10</td></tr></table>                               |
| Size                   | 15                                                                                                                                                                          |
| Strikethrough          | false                                                                                                                                                                       |
| Underline              | false                                                                                                                                                                       |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                        |
| Width                  | 160                                                                                                                                                                         |
| X                      | 0                                                                                                                                                                           |
| Y                      | 0                                                                                                                                                                           |
| ZIndex                 | 28                                                                                                                                                                          |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                                             |
| ------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.Fill, -15%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>                 |
| Color               | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table>                                                                                                                                                                                                                                                                                                             |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table>                     |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(161, 159, 157, 1)</td></tr><tr><td style="background-color:#A19F9D"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table>               |
| DisabledFill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(242, 242, 241, 0)</td></tr><tr><td style="background-color:#F2F2F1"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table></td></tr></table>               |
| Fill                | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 120, 212, 1)</td></tr><tr><td style="background-color:#0078D4"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table></td></tr></table>                   |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                                  |
| HoverBorderColor    | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.BorderColor, 20%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>           |
| HoverColor          | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table>                                                                                                                                                                                                                                                                                                             |
| HoverFill           | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(16, 110, 190, 1)</td></tr><tr><td style="background-color:#106EBE"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(RGBA(56, 96, 178, 1), -20%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table> |
| PressedBorderColor  | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 69, 120, 1)</td></tr><tr><td style="background-color:#004578"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.Fill</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>                               |
| PressedColor        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.Fill</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>                            |
| PressedFill         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(16, 110, 190, 1)</td></tr><tr><td style="background-color:#106EBE"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.Color</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>                            |

### Child & Parent Controls

| Property       | Value                            |
| -------------- | -------------------------------- |
| Parent Control | ConfirmDeleteButtonBarContainer1 |

## ConfirmDeleteButtonBarContainer1

| Property                                                                      | Value                               |
| ----------------------------------------------------------------------------- | ----------------------------------- |
| ![horizontalAutoLayoutContainer](resources/horizontalAutoLayoutContainer.png) | Type: horizontalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                 |
| -------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.None<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">200<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Horizontal<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">15<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.Center<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">500<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| X                    | 0                                                                                                                                                                     |
| Y                    | 0                                                                                                                                                                     |
| ZIndex               | 26                                                                                                                                                                    |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value                         |
| -------------- | ----------------------------- |
| Child Control  | CancelDeleteButton1           |
| Child Control  | ConfirmDeleteButton1          |
| Parent Control | DeleteConfirmDialogContainer1 |

## ConfirmDeletionLabel1

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property | Value                                                                                                                                                                                          |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Live     | Live.Off                                                                                                                                                                                       |
| Role     | TextRole.Default                                                                                                                                                                               |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Are you sure you want to delete this record?"<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |

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
| Height                 | 40                                                                                                                                                                          |
| Italic                 | false                                                                                                                                                                       |
| LineHeight             | 1.2                                                                                                                                                                         |
| Overflow               | Overflow.Hidden                                                                                                                                                             |
| PaddingBottom          | 5                                                                                                                                                                           |
| PaddingLeft            | 5                                                                                                                                                                           |
| PaddingRight           | 5                                                                                                                                                                           |
| PaddingTop             | 5                                                                                                                                                                           |
| Size                   | 13                                                                                                                                                                          |
| Strikethrough          | false                                                                                                                                                                       |
| Underline              | false                                                                                                                                                                       |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                        |
| Width                  | 150                                                                                                                                                                         |
| X                      | 0                                                                                                                                                                           |
| Y                      | 0                                                                                                                                                                           |
| ZIndex                 | 25                                                                                                                                                                          |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>          |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(50, 49, 48, 1)</td></tr><tr><td style="background-color:#323130"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>          |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table></td></tr></table>          |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(161, 159, 157, 1)</td></tr><tr><td style="background-color:#A19F9D"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                     |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                     |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverBorderColor    | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverColor          | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                          |
| HoverFill           | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                           |
| PressedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| PressedColor        | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                          |
| PressedFill         | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                           |

### Child & Parent Controls

| Property       | Value                         |
| -------------- | ----------------------------- |
| Parent Control | DeleteConfirmDialogContainer1 |

## Container1

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
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">200<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
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

| Property       | Value             |
| -------------- | ----------------- |
| Child Control  | ScreenContainer1  |
| Parent Control | cnt\_body\_rec\_4 |

## Container9\_4

| Property                                                                      | Value                               |
| ----------------------------------------------------------------------------- | ----------------------------------- |
| ![horizontalAutoLayoutContainer](resources/horizontalAutoLayoutContainer.png) | Type: horizontalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.Light<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">200<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Horizontal<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
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
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Component1_6.Menu_Width<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| X                    | 0                                                                                                                                                                    |
| Y                    | 0                                                                                                                                                                    |
| ZIndex               | 1                                                                                                                                                                    |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value             |
| -------------- | ----------------- |
| Child Control  | Component1\_6     |
| Parent Control | cnt\_body\_rec\_4 |

## DataCardKey1\_1

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property | Value                                                                                                                                                              |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Live     | Live.Off                                                                                                                                                           |
| Role     | TextRole.Default                                                                                                                                                   |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayName<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                          |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Align                  | Align.Left                                                                                                                                                                     |
| AutoHeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table>    |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                   |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                               |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                   |
| Font                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Font.'Segoe UI'<td style="background-color:#ffcccc; width:50%;">Font.'Open Sans'</td></tr></table>      |
| FontWeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">FontWeight.Semibold<td style="background-color:#ffcccc; width:50%;">FontWeight.Normal</td></tr></table> |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">34<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                                 |
| Italic                 | false                                                                                                                                                                          |
| LineHeight             | 1.2                                                                                                                                                                            |
| Overflow               | Overflow.Hidden                                                                                                                                                                |
| PaddingBottom          | 5                                                                                                                                                                              |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                   |
| PaddingRight           | 5                                                                                                                                                                              |
| PaddingTop             | 5                                                                                                                                                                              |
| Size                   | 13                                                                                                                                                                             |
| Strikethrough          | false                                                                                                                                                                          |
| Underline              | false                                                                                                                                                                          |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                           |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">(Parent.Width - 60) * 0.4<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>         |
| Wrap                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                |
| X                      | 30                                                                                                                                                                             |
| Y                      | 10 + (DataCardValue1\_1.Height \/ 2) \- (Self.Height \/ 2)                                                                                                                     |
| ZIndex                 | 1                                                                                                                                                                              |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>          |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(50, 49, 48, 1)</td></tr><tr><td style="background-color:#323130"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>          |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table></td></tr></table>          |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(161, 159, 157, 1)</td></tr><tr><td style="background-color:#A19F9D"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                     |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                     |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverBorderColor    | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverColor          | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                          |
| HoverFill           | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                           |
| PressedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| PressedColor        | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                          |
| PressedFill         | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                           |

### Child & Parent Controls

| Property       | Value              |
| -------------- | ------------------ |
| Parent Control | Name\_DataCard1\_1 |

## DataCardKey2

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property | Value                                                                                                                                                              |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Live     | Live.Off                                                                                                                                                           |
| Role     | TextRole.Default                                                                                                                                                   |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayName<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                          |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Align                  | Align.Left                                                                                                                                                                     |
| AutoHeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table>    |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                   |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                               |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                   |
| Font                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Font.'Segoe UI'<td style="background-color:#ffcccc; width:50%;">Font.'Open Sans'</td></tr></table>      |
| FontWeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">FontWeight.Semibold<td style="background-color:#ffcccc; width:50%;">FontWeight.Normal</td></tr></table> |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">34<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                                 |
| Italic                 | false                                                                                                                                                                          |
| LineHeight             | 1.2                                                                                                                                                                            |
| Overflow               | Overflow.Hidden                                                                                                                                                                |
| PaddingBottom          | 5                                                                                                                                                                              |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                   |
| PaddingRight           | 5                                                                                                                                                                              |
| PaddingTop             | 5                                                                                                                                                                              |
| Size                   | 13                                                                                                                                                                             |
| Strikethrough          | false                                                                                                                                                                          |
| Underline              | false                                                                                                                                                                          |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                           |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 60<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>                 |
| Wrap                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                |
| X                      | 30                                                                                                                                                                             |
| Y                      | 10                                                                                                                                                                             |
| ZIndex                 | 1                                                                                                                                                                              |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>          |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(50, 49, 48, 1)</td></tr><tr><td style="background-color:#323130"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>          |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table></td></tr></table>          |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(161, 159, 157, 1)</td></tr><tr><td style="background-color:#A19F9D"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                     |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                     |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverBorderColor    | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverColor          | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                          |
| HoverFill           | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                           |
| PressedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| PressedColor        | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                          |
| PressedFill         | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                           |

### Child & Parent Controls

| Property       | Value               |
| -------------- | ------------------- |
| Parent Control | Username\_DataCard1 |

## DataCardKey3

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property | Value                                                                                                                                                              |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Live     | Live.Off                                                                                                                                                           |
| Role     | TextRole.Default                                                                                                                                                   |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayName<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                          |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Align                  | Align.Left                                                                                                                                                                     |
| AutoHeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table>    |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                   |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                               |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                   |
| Font                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Font.'Segoe UI'<td style="background-color:#ffcccc; width:50%;">Font.'Open Sans'</td></tr></table>      |
| FontWeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">FontWeight.Semibold<td style="background-color:#ffcccc; width:50%;">FontWeight.Normal</td></tr></table> |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">34<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                                 |
| Italic                 | false                                                                                                                                                                          |
| LineHeight             | 1.2                                                                                                                                                                            |
| Overflow               | Overflow.Hidden                                                                                                                                                                |
| PaddingBottom          | 5                                                                                                                                                                              |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                   |
| PaddingRight           | 5                                                                                                                                                                              |
| PaddingTop             | 5                                                                                                                                                                              |
| Size                   | 13                                                                                                                                                                             |
| Strikethrough          | false                                                                                                                                                                          |
| Underline              | false                                                                                                                                                                          |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                           |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 60<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>                 |
| Wrap                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                |
| X                      | 30                                                                                                                                                                             |
| Y                      | 10                                                                                                                                                                             |
| ZIndex                 | 1                                                                                                                                                                              |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>          |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(50, 49, 48, 1)</td></tr><tr><td style="background-color:#323130"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>          |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table></td></tr></table>          |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(161, 159, 157, 1)</td></tr><tr><td style="background-color:#A19F9D"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                     |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                     |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverBorderColor    | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverColor          | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                          |
| HoverFill           | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                           |
| PressedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| PressedColor        | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                          |
| PressedFill         | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                           |

### Child & Parent Controls

| Property       | Value                |
| -------------- | -------------------- |
| Parent Control | Passwords\_DataCard1 |

## DataCardKey4

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property | Value                                                                                                                                                              |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Live     | Live.Off                                                                                                                                                           |
| Role     | TextRole.Default                                                                                                                                                   |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayName<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                          |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Align                  | Align.Left                                                                                                                                                                     |
| AutoHeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table>    |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                   |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                               |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                   |
| Font                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Font.'Segoe UI'<td style="background-color:#ffcccc; width:50%;">Font.'Open Sans'</td></tr></table>      |
| FontWeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">FontWeight.Semibold<td style="background-color:#ffcccc; width:50%;">FontWeight.Normal</td></tr></table> |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">34<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                                 |
| Italic                 | false                                                                                                                                                                          |
| LineHeight             | 1.2                                                                                                                                                                            |
| Overflow               | Overflow.Hidden                                                                                                                                                                |
| PaddingBottom          | 5                                                                                                                                                                              |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                   |
| PaddingRight           | 5                                                                                                                                                                              |
| PaddingTop             | 5                                                                                                                                                                              |
| Size                   | 13                                                                                                                                                                             |
| Strikethrough          | false                                                                                                                                                                          |
| Underline              | false                                                                                                                                                                          |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                           |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 60<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>                 |
| Wrap                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                |
| X                      | 30                                                                                                                                                                             |
| Y                      | 10                                                                                                                                                                             |
| ZIndex                 | 1                                                                                                                                                                              |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>          |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(50, 49, 48, 1)</td></tr><tr><td style="background-color:#323130"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>          |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table></td></tr></table>          |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(161, 159, 157, 1)</td></tr><tr><td style="background-color:#A19F9D"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                     |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                     |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverBorderColor    | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverColor          | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                          |
| HoverFill           | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                           |
| PressedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| PressedColor        | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                          |
| PressedFill         | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                           |

### Child & Parent Controls

| Property       | Value                 |
| -------------- | --------------------- |
| Parent Control | User\_Type\_DataCard1 |

## DataCardKey5\_1

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property | Value                                                                                                                                                              |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Live     | Live.Off                                                                                                                                                           |
| Role     | TextRole.Default                                                                                                                                                   |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayName<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                  |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align                  | Align.Left                                                                                                                                                             |
| AutoHeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| BorderStyle            | BorderStyle.Solid                                                                                                                                                      |
| BorderThickness        | 0                                                                                                                                                                      |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                       |
| FocusedBorderThickness | 0                                                                                                                                                                      |
| Font                   | Font.'Open Sans'                                                                                                                                                       |
| FontWeight             | FontWeight.Normal                                                                                                                                                      |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">34<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                         |
| Italic                 | false                                                                                                                                                                  |
| LineHeight             | 1.2                                                                                                                                                                    |
| Overflow               | Overflow.Hidden                                                                                                                                                        |
| PaddingBottom          | 5                                                                                                                                                                      |
| PaddingLeft            | 5                                                                                                                                                                      |
| PaddingRight           | 5                                                                                                                                                                      |
| PaddingTop             | 5                                                                                                                                                                      |
| Size                   | 13                                                                                                                                                                     |
| Strikethrough          | false                                                                                                                                                                  |
| Underline              | false                                                                                                                                                                  |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                   |
| Visible                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">(Parent.Width - 60) * 0.4<td style="background-color:#ffcccc; width:50%;">150</td></tr></table> |
| Wrap                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| X                      | 30                                                                                                                                                                     |
| Y                      | 10 + (AddPicture1\_1.Height \/ 2) \- (Self.Height \/ 2)                                                                                                                |
| ZIndex                 | 1                                                                                                                                                                      |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                      |
| ------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table> |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table> |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table>                                                                                                                                                                                                                                                                                         |
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

| Property       | Value                |
| -------------- | -------------------- |
| Parent Control | Imagem\_DataCard1\_1 |

## DataCardValue1\_1

| Property                    | Value      |
| --------------------------- | ---------- |
| ![text](resources/text.png) | Type: text |

### Data

| Property    | Value                                                                                                                                                                |
| ----------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Default     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Default<td style="background-color:#ffcccc; width:50%;">"Text input"</td></tr></table> |
| DelayOutput | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;">false</td></tr></table>                  |
| MaxLength   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.MaxLength<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| Tooltip     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayName<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |

### Design

| Property               | Value                                                                                                                                                                        |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align                  | Align.Left                                                                                                                                                                   |
| BorderStyle            | BorderStyle.Solid                                                                                                                                                            |
| BorderThickness        | 2                                                                                                                                                                            |
| DisplayMode            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayMode<td style="background-color:#ffcccc; width:50%;">DisplayMode.Edit</td></tr></table> |
| FocusedBorderThickness | 4                                                                                                                                                                            |
| Font                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Font.'Segoe UI'<td style="background-color:#ffcccc; width:50%;">Font.'Open Sans'</td></tr></table>    |
| FontWeight             | FontWeight.Normal                                                                                                                                                            |
| Format                 | TextFormat.Text                                                                                                                                                              |
| Height                 | 40                                                                                                                                                                           |
| Italic                 | false                                                                                                                                                                        |
| Mode                   | TextMode.SingleLine                                                                                                                                                          |
| PaddingBottom          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">5<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                  |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">5<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                  |
| PaddingRight           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">5<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                  |
| PaddingTop             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">5<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                  |
| RadiusBottomLeft       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                 |
| RadiusBottomRight      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                 |
| RadiusTopLeft          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                 |
| RadiusTopRight         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                 |
| Size                   | 13                                                                                                                                                                           |
| Strikethrough          | false                                                                                                                                                                        |
| Underline              | false                                                                                                                                                                        |
| VirtualKeyboardMode    | VirtualKeyboardMode.Auto                                                                                                                                                     |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">(Parent.Width - 60) * 0.6<td style="background-color:#ffcccc; width:50%;">320</td></tr></table>       |
| X                      | DataCardKey1\_1.X + DataCardKey1\_1.Width                                                                                                                                    |
| Y                      | 10                                                                                                                                                                           |
| ZIndex                 | 2                                                                                                                                                                            |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | If(IsBlank(Parent.Error), Parent.BorderColor, Color.Red)                                                                                                                                                                                                                                                                                                                                                            |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(50, 49, 48, 1)</td></tr><tr><td style="background-color:#323130"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>          |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table>       |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(161, 159, 157, 1)</td></tr><tr><td style="background-color:#A19F9D"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(242, 242, 241, 0)</td></tr><tr><td style="background-color:#F2F2F1"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table>                                                                                                                                                                                                                                                                                               |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverBorderColor    | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(16, 110, 190, 1)</td></tr><tr><td style="background-color:#106EBE"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>     |
| HoverColor          | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(50, 49, 48, 1)</td></tr><tr><td style="background-color:#323130"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>          |
| HoverFill           | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(186, 202, 226, 1)</td></tr><tr><td style="background-color:#BACAE2"></td></tr></table></td></tr></table> |
| PressedBorderColor  | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 120, 212, 1)</td></tr><tr><td style="background-color:#0078D4"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.HoverBorderColor</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>    |
| PressedColor        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(50, 49, 48, 1)</td></tr><tr><td style="background-color:#323130"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.Color</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>                |
| PressedFill         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.Fill</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>              |

### Child & Parent Controls

| Property       | Value              |
| -------------- | ------------------ |
| Parent Control | Name\_DataCard1\_1 |

## DataCardValue2

| Property                    | Value      |
| --------------------------- | ---------- |
| ![text](resources/text.png) | Type: text |

### Data

| Property    | Value                                                                                                                                                                |
| ----------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Default     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Default<td style="background-color:#ffcccc; width:50%;">"Text input"</td></tr></table> |
| DelayOutput | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;">false</td></tr></table>                  |
| MaxLength   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.MaxLength<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| Tooltip     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayName<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |

### Design

| Property               | Value                                                                                                                                                                        |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align                  | Align.Left                                                                                                                                                                   |
| BorderStyle            | BorderStyle.Solid                                                                                                                                                            |
| BorderThickness        | 2                                                                                                                                                                            |
| DisplayMode            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayMode<td style="background-color:#ffcccc; width:50%;">DisplayMode.Edit</td></tr></table> |
| FocusedBorderThickness | 4                                                                                                                                                                            |
| Font                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Font.'Segoe UI'<td style="background-color:#ffcccc; width:50%;">Font.'Open Sans'</td></tr></table>    |
| FontWeight             | FontWeight.Normal                                                                                                                                                            |
| Format                 | TextFormat.Text                                                                                                                                                              |
| Height                 | 40                                                                                                                                                                           |
| Italic                 | false                                                                                                                                                                        |
| Mode                   | TextMode.SingleLine                                                                                                                                                          |
| PaddingBottom          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">5<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                  |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">5<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                  |
| PaddingRight           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">5<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                  |
| PaddingTop             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">5<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                  |
| RadiusBottomLeft       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                 |
| RadiusBottomRight      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                 |
| RadiusTopLeft          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                 |
| RadiusTopRight         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                 |
| Size                   | 13                                                                                                                                                                           |
| Strikethrough          | false                                                                                                                                                                        |
| Underline              | false                                                                                                                                                                        |
| VirtualKeyboardMode    | VirtualKeyboardMode.Auto                                                                                                                                                     |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 60<td style="background-color:#ffcccc; width:50%;">320</td></tr></table>               |
| X                      | 30                                                                                                                                                                           |
| Y                      | DataCardKey2.Y + DataCardKey2.Height + 5                                                                                                                                     |
| ZIndex                 | 2                                                                                                                                                                            |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | If(IsBlank(Parent.Error), Parent.BorderColor, Color.Red)                                                                                                                                                                                                                                                                                                                                                            |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(50, 49, 48, 1)</td></tr><tr><td style="background-color:#323130"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>          |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table>       |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(161, 159, 157, 1)</td></tr><tr><td style="background-color:#A19F9D"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(242, 242, 241, 0)</td></tr><tr><td style="background-color:#F2F2F1"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table>                                                                                                                                                                                                                                                                                               |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverBorderColor    | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(16, 110, 190, 1)</td></tr><tr><td style="background-color:#106EBE"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>     |
| HoverColor          | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(50, 49, 48, 1)</td></tr><tr><td style="background-color:#323130"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>          |
| HoverFill           | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(186, 202, 226, 1)</td></tr><tr><td style="background-color:#BACAE2"></td></tr></table></td></tr></table> |
| PressedBorderColor  | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 120, 212, 1)</td></tr><tr><td style="background-color:#0078D4"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.HoverBorderColor</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>    |
| PressedColor        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(50, 49, 48, 1)</td></tr><tr><td style="background-color:#323130"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.Color</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>                |
| PressedFill         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.Fill</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>              |

### Child & Parent Controls

| Property       | Value               |
| -------------- | ------------------- |
| Parent Control | Username\_DataCard1 |

## DataCardValue3

| Property                    | Value      |
| --------------------------- | ---------- |
| ![text](resources/text.png) | Type: text |

### Data

| Property    | Value                                                                                                                                                                |
| ----------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Default     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Default<td style="background-color:#ffcccc; width:50%;">"Text input"</td></tr></table> |
| DelayOutput | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;">false</td></tr></table>                  |
| MaxLength   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.MaxLength<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| Tooltip     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayName<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |

### Design

| Property               | Value                                                                                                                                                                        |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align                  | Align.Left                                                                                                                                                                   |
| BorderStyle            | BorderStyle.Solid                                                                                                                                                            |
| BorderThickness        | 2                                                                                                                                                                            |
| DisplayMode            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayMode<td style="background-color:#ffcccc; width:50%;">DisplayMode.Edit</td></tr></table> |
| FocusedBorderThickness | 4                                                                                                                                                                            |
| Font                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Font.'Segoe UI'<td style="background-color:#ffcccc; width:50%;">Font.'Open Sans'</td></tr></table>    |
| FontWeight             | FontWeight.Normal                                                                                                                                                            |
| Format                 | TextFormat.Text                                                                                                                                                              |
| Height                 | 40                                                                                                                                                                           |
| Italic                 | false                                                                                                                                                                        |
| Mode                   | TextMode.SingleLine                                                                                                                                                          |
| PaddingBottom          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">5<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                  |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">5<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                  |
| PaddingRight           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">5<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                  |
| PaddingTop             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">5<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                  |
| RadiusBottomLeft       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                 |
| RadiusBottomRight      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                 |
| RadiusTopLeft          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                 |
| RadiusTopRight         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                 |
| Size                   | 13                                                                                                                                                                           |
| Strikethrough          | false                                                                                                                                                                        |
| Underline              | false                                                                                                                                                                        |
| VirtualKeyboardMode    | VirtualKeyboardMode.Auto                                                                                                                                                     |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 60<td style="background-color:#ffcccc; width:50%;">320</td></tr></table>               |
| X                      | 30                                                                                                                                                                           |
| Y                      | DataCardKey3.Y + DataCardKey3.Height + 5                                                                                                                                     |
| ZIndex                 | 2                                                                                                                                                                            |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | If(IsBlank(Parent.Error), Parent.BorderColor, Color.Red)                                                                                                                                                                                                                                                                                                                                                            |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(50, 49, 48, 1)</td></tr><tr><td style="background-color:#323130"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>          |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table>       |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(161, 159, 157, 1)</td></tr><tr><td style="background-color:#A19F9D"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(242, 242, 241, 0)</td></tr><tr><td style="background-color:#F2F2F1"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table>                                                                                                                                                                                                                                                                                               |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverBorderColor    | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(16, 110, 190, 1)</td></tr><tr><td style="background-color:#106EBE"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>     |
| HoverColor          | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(50, 49, 48, 1)</td></tr><tr><td style="background-color:#323130"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>          |
| HoverFill           | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(186, 202, 226, 1)</td></tr><tr><td style="background-color:#BACAE2"></td></tr></table></td></tr></table> |
| PressedBorderColor  | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 120, 212, 1)</td></tr><tr><td style="background-color:#0078D4"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.HoverBorderColor</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>    |
| PressedColor        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(50, 49, 48, 1)</td></tr><tr><td style="background-color:#323130"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.Color</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>                |
| PressedFill         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.Fill</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>              |

### Child & Parent Controls

| Property       | Value                |
| -------------- | -------------------- |
| Parent Control | Passwords\_DataCard1 |

## DataCardValue4

| Property                            | Value          |
| ----------------------------------- | -------------- |
| ![combobox](resources/combobox.png) | Type: combobox |

### Data

| Property             | Value                                                                                                                                                                                                                                           |
| -------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DefaultSelectedItems | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">[Parent.Default]<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                      |
| DisplayFields        | \["Value1"\]                                                                                                                                                                                                                                    |
| IsSearchable         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                 |
| Items                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Choices(User_Type)<td style="background-color:#ffcccc; width:50%;">ComboBoxSample</td></tr></table>                                                                      |
| NavigateFields       | \[\]                                                                                                                                                                                                                                            |
| SearchFields         | \["Value1"\]                                                                                                                                                                                                                                    |
| SearchItems          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Search(ComboBoxSample, Self.SearchText, "Value1")<td style="background-color:#ffcccc; width:50%;">Search(ComboBoxSample,ComboBox1.SearchText,"Value1")</td></tr></table> |
| SelectMultiple       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                 |
| Tooltip              | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayName<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                    |

### Design

| Property                  | Value                                                                                                                                                                                                                                                                                                                                                                                                                              |
| ------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle               | BorderStyle.Solid                                                                                                                                                                                                                                                                                                                                                                                                                  |
| BorderThickness           | 2                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| ChevronBackground         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(245, 245, 245, 1)</td></tr><tr><td style="background-color:#F5F5F5"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table></td></tr></table>                  |
| ChevronDisabledBackground | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(242, 242, 241, 0)</td></tr><tr><td style="background-color:#F2F2F1"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table>                |
| ChevronDisabledFill       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(161, 159, 157, 1)</td></tr><tr><td style="background-color:#A19F9D"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table></td></tr></table>                |
| ChevronFill               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(50, 49, 48, 1)</td></tr><tr><td style="background-color:#323130"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td></tr></table>                   |
| ChevronHoverBackground    | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(245, 245, 245, 1)</td></tr><tr><td style="background-color:#F5F5F5"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(RGBA(56, 96, 178, 1), -20%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table> |
| ChevronHoverFill          | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(50, 49, 48, 1)</td></tr><tr><td style="background-color:#323130"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td></tr></table>                   |
| DisplayMode               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayMode<td style="background-color:#ffcccc; width:50%;">DisplayMode.Edit</td></tr></table>                                                                                                                                                                                                                                                       |
| FocusedBorderThickness    | 4                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Font                      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Font.'Segoe UI'<td style="background-color:#ffcccc; width:50%;">Font.'Open Sans'</td></tr></table>                                                                                                                                                                                                                                                          |
| FontWeight                | FontWeight.Normal                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Height                    | 40                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| MoreItemsButtonColor      | Self.ChevronBackground                                                                                                                                                                                                                                                                                                                                                                                                             |
| PaddingBottom             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">5<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                                                                                                                                                                                                        |
| PaddingLeft               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Self.DisplayMode = DisplayMode.Edit, 5, 0)<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                                                                                                                                                            |
| PaddingRight              | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">5<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                                                                                                                                                                                                        |
| PaddingTop                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">5<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                                                                                                                                                                                                        |
| SelectionTagColor         | Self.HoverColor                                                                                                                                                                                                                                                                                                                                                                                                                    |
| SelectionTagFill          | Self.HoverFill                                                                                                                                                                                                                                                                                                                                                                                                                     |
| Size                      | 13                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| Template                  | ListItemTemplate.Single                                                                                                                                                                                                                                                                                                                                                                                                            |
| Width                     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 60<td style="background-color:#ffcccc; width:50%;">328</td></tr></table>                                                                                                                                                                                                                                                                     |
| X                         | 30                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| Y                         | DataCardKey4.Y + DataCardKey4.Height + 5                                                                                                                                                                                                                                                                                                                                                                                           |
| ZIndex                    | 2                                                                                                                                                                                                                                                                                                                                                                                                                                  |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                                        |
| ------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | If(IsBlank(Parent.Error), Parent.BorderColor, Color.Red)                                                                                                                                                                                                                                                                                                                                                                     |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(50, 49, 48, 1)</td></tr><tr><td style="background-color:#323130"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>                   |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table>                |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(161, 159, 157, 1)</td></tr><tr><td style="background-color:#A19F9D"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table>          |
| DisabledFill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(242, 242, 241, 0)</td></tr><tr><td style="background-color:#F2F2F1"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table></td></tr></table>          |
| Fill                | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(245, 245, 245, 1)</td></tr><tr><td style="background-color:#F5F5F5"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td></tr></table>          |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                             |
| HoverBorderColor    | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(16, 110, 190, 1)</td></tr><tr><td style="background-color:#106EBE"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.BorderColor, 15%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table> |
| HoverColor          | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(50, 49, 48, 1)</td></tr><tr><td style="background-color:#323130"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>                   |
| HoverFill           | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(245, 245, 245, 1)</td></tr><tr><td style="background-color:#F5F5F5"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(186, 202, 226, 1)</td></tr><tr><td style="background-color:#BACAE2"></td></tr></table></td></tr></table>          |
| PressedBorderColor  | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(16, 110, 190, 1)</td></tr><tr><td style="background-color:#106EBE"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.HoverBorderColor</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>            |
| PressedColor        | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table>                                                                                                                                                                                                                                                                                                        |
| PressedFill         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 120, 212, 1)</td></tr><tr><td style="background-color:#0078D4"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>               |
| SelectionColor      | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table>                                                                                                                                                                                                                                                                                                        |
| SelectionFill       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 120, 212, 1)</td></tr><tr><td style="background-color:#0078D4"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table></td></tr></table>              |

### Child & Parent Controls

| Property       | Value                 |
| -------------- | --------------------- |
| Parent Control | User\_Type\_DataCard1 |

## DeleteConfirmDialogContainer1

| Property                                                                  | Value                             |
| ------------------------------------------------------------------------- | --------------------------------- |
| ![verticalAutoLayoutContainer](resources/verticalAutoLayoutContainer.png) | Type: verticalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                 |
| -------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.Light<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">200<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Vertical<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| Visible              | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(deleteMode, true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| X                    | 0                                                                                                                                                                     |
| Y                    | 0                                                                                                                                                                     |
| ZIndex               | 24                                                                                                                                                                    |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value                            |
| -------------- | -------------------------------- |
| Child Control  | ConfirmDeletionLabel1            |
| Child Control  | ConfirmDeleteButtonBarContainer1 |
| Parent Control | BodyContainer1                   |

## DeleteIconButton1

| Property                    | Value      |
| --------------------------- | ---------- |
| ![icon](resources/icon.png) | Type: icon |

### Behavior

| Property | Value                                                                                                                                                                                                                                           |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">UpdateContext({ deleteMode: true, deleteCancelled: false, selectedRecord: RecordsGallery1.Selected })<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property | Value                                                                                                                                              |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tooltip  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Delete"<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                           |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                     |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| DisplayMode            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">50<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                    |
| Icon                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Icon.Trash<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| PaddingBottom          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">12<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                    |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">12<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                    |
| PaddingRight           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">12<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                    |
| PaddingTop             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">12<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                    |
| TabIndex               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| Visible                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">And(!editMode, !newMode, !deleteMode)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">50<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                    |
| X                      | 0                                                                                                                                                                               |
| Y                      | 0                                                                                                                                                                               |
| ZIndex                 | 21                                                                                                                                                                              |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                      |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(252, 65, 123, 1)</td></tr><tr><td style="background-color:#FC417B"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>  |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(245, 245, 245, 1)</td></tr><tr><td style="background-color:#F5F5F5"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(225, 223, 221, 1)</td></tr><tr><td style="background-color:#E1DFDD"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| Fill                | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                           |
| HoverBorderColor    | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| HoverColor          | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(16, 110, 190, 1)</td></tr><tr><td style="background-color:#106EBE"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>  |
| HoverFill           | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| PressedBorderColor  | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| PressedColor        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(16, 110, 190, 1)</td></tr><tr><td style="background-color:#106EBE"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>  |
| PressedFill         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |

### Child & Parent Controls

| Property       | Value                          |
| -------------- | ------------------------------ |
| Parent Control | SelectedRecordHeaderContainer1 |

## EditIconButton1

| Property                    | Value      |
| --------------------------- | ---------- |
| ![icon](resources/icon.png) | Type: icon |

### Behavior

| Property | Value                                                                                                                                                                                                                 |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">UpdateContext({ editMode: true, selectedRecord: RecordsGallery1.Selected })<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property | Value                                                                                                                                            |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| Tooltip  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Edit"<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                           |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                     |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| DisplayMode            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">50<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                    |
| Icon                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Icon.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                             |
| PaddingBottom          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">12<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                    |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">12<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                    |
| PaddingRight           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">12<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                    |
| PaddingTop             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">12<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                    |
| TabIndex               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| Visible                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">And(!editMode, !newMode, !deleteMode)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">50<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                    |
| X                      | 0                                                                                                                                                                               |
| Y                      | 0                                                                                                                                                                               |
| ZIndex                 | 20                                                                                                                                                                              |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                      |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(252, 65, 123, 1)</td></tr><tr><td style="background-color:#FC417B"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>  |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(245, 245, 245, 1)</td></tr><tr><td style="background-color:#F5F5F5"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(225, 223, 221, 1)</td></tr><tr><td style="background-color:#E1DFDD"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| Fill                | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                           |
| HoverBorderColor    | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| HoverColor          | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(16, 110, 190, 1)</td></tr><tr><td style="background-color:#106EBE"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>  |
| HoverFill           | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| PressedBorderColor  | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| PressedColor        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(16, 110, 190, 1)</td></tr><tr><td style="background-color:#106EBE"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>  |
| PressedFill         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |

### Child & Parent Controls

| Property       | Value                          |
| -------------- | ------------------------------ |
| Parent Control | SelectedRecordHeaderContainer1 |

## ErrorMessage1\_1

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property | Value                                                                                                                                                            |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Live     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Live.Assertive<td style="background-color:#ffcccc; width:50%;">Live.Off</td></tr></table> |
| Role     | TextRole.Default                                                                                                                                                 |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Error<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table>     |

### Design

| Property               | Value                                                                                                                                                                          |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Align                  | Align.Left                                                                                                                                                                     |
| AutoHeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table>    |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                   |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                               |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                   |
| Font                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Font.'Segoe UI'<td style="background-color:#ffcccc; width:50%;">Font.'Open Sans'</td></tr></table>      |
| FontWeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">FontWeight.Semibold<td style="background-color:#ffcccc; width:50%;">FontWeight.Normal</td></tr></table> |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                                 |
| Italic                 | false                                                                                                                                                                          |
| LineHeight             | 1.2                                                                                                                                                                            |
| Overflow               | Overflow.Hidden                                                                                                                                                                |
| PaddingBottom          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                   |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                   |
| PaddingRight           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                   |
| PaddingTop             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                   |
| Size                   | 13                                                                                                                                                                             |
| Strikethrough          | false                                                                                                                                                                          |
| Underline              | false                                                                                                                                                                          |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                           |
| Visible                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayMode=DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 60<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>                 |
| X                      | 30                                                                                                                                                                             |
| Y                      | DataCardValue1\_1.Y + DataCardValue1\_1.Height                                                                                                                                 |
| ZIndex                 | 3                                                                                                                                                                              |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                           |
| ------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>      |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(168, 0, 0, 1)</td></tr><tr><td style="background-color:#A80000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>       |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table></td></tr></table>      |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(168, 0, 0, 1)</td></tr><tr><td style="background-color:#A80000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                 |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                 |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                |
| HoverBorderColor    | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                |
| HoverColor          | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                      |
| HoverFill           | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                       |
| PressedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                |
| PressedColor        | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                      |
| PressedFill         | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                       |

### Child & Parent Controls

| Property       | Value              |
| -------------- | ------------------ |
| Parent Control | Name\_DataCard1\_1 |

## ErrorMessage2

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property | Value                                                                                                                                                            |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Live     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Live.Assertive<td style="background-color:#ffcccc; width:50%;">Live.Off</td></tr></table> |
| Role     | TextRole.Default                                                                                                                                                 |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Error<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table>     |

### Design

| Property               | Value                                                                                                                                                                          |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Align                  | Align.Left                                                                                                                                                                     |
| AutoHeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table>    |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                   |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                               |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                   |
| Font                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Font.'Segoe UI'<td style="background-color:#ffcccc; width:50%;">Font.'Open Sans'</td></tr></table>      |
| FontWeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">FontWeight.Semibold<td style="background-color:#ffcccc; width:50%;">FontWeight.Normal</td></tr></table> |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                                 |
| Italic                 | false                                                                                                                                                                          |
| LineHeight             | 1.2                                                                                                                                                                            |
| Overflow               | Overflow.Hidden                                                                                                                                                                |
| PaddingBottom          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                   |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                   |
| PaddingRight           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                   |
| PaddingTop             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                   |
| Size                   | 13                                                                                                                                                                             |
| Strikethrough          | false                                                                                                                                                                          |
| Underline              | false                                                                                                                                                                          |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                           |
| Visible                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayMode=DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 60<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>                 |
| X                      | 30                                                                                                                                                                             |
| Y                      | DataCardValue2.Y + DataCardValue2.Height                                                                                                                                       |
| ZIndex                 | 3                                                                                                                                                                              |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                           |
| ------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>      |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(168, 0, 0, 1)</td></tr><tr><td style="background-color:#A80000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>       |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table></td></tr></table>      |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(168, 0, 0, 1)</td></tr><tr><td style="background-color:#A80000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                 |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                 |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                |
| HoverBorderColor    | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                |
| HoverColor          | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                      |
| HoverFill           | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                       |
| PressedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                |
| PressedColor        | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                      |
| PressedFill         | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                       |

### Child & Parent Controls

| Property       | Value               |
| -------------- | ------------------- |
| Parent Control | Username\_DataCard1 |

## ErrorMessage3

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property | Value                                                                                                                                                            |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Live     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Live.Assertive<td style="background-color:#ffcccc; width:50%;">Live.Off</td></tr></table> |
| Role     | TextRole.Default                                                                                                                                                 |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Error<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table>     |

### Design

| Property               | Value                                                                                                                                                                          |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Align                  | Align.Left                                                                                                                                                                     |
| AutoHeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table>    |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                   |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                               |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                   |
| Font                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Font.'Segoe UI'<td style="background-color:#ffcccc; width:50%;">Font.'Open Sans'</td></tr></table>      |
| FontWeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">FontWeight.Semibold<td style="background-color:#ffcccc; width:50%;">FontWeight.Normal</td></tr></table> |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                                 |
| Italic                 | false                                                                                                                                                                          |
| LineHeight             | 1.2                                                                                                                                                                            |
| Overflow               | Overflow.Hidden                                                                                                                                                                |
| PaddingBottom          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                   |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                   |
| PaddingRight           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                   |
| PaddingTop             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                   |
| Size                   | 13                                                                                                                                                                             |
| Strikethrough          | false                                                                                                                                                                          |
| Underline              | false                                                                                                                                                                          |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                           |
| Visible                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayMode=DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 60<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>                 |
| X                      | 30                                                                                                                                                                             |
| Y                      | DataCardValue3.Y + DataCardValue3.Height                                                                                                                                       |
| ZIndex                 | 3                                                                                                                                                                              |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                           |
| ------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>      |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(168, 0, 0, 1)</td></tr><tr><td style="background-color:#A80000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>       |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table></td></tr></table>      |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(168, 0, 0, 1)</td></tr><tr><td style="background-color:#A80000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                 |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                 |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                |
| HoverBorderColor    | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                |
| HoverColor          | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                      |
| HoverFill           | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                       |
| PressedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                |
| PressedColor        | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                      |
| PressedFill         | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                       |

### Child & Parent Controls

| Property       | Value                |
| -------------- | -------------------- |
| Parent Control | Passwords\_DataCard1 |

## ErrorMessage4

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property | Value                                                                                                                                                            |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Live     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Live.Assertive<td style="background-color:#ffcccc; width:50%;">Live.Off</td></tr></table> |
| Role     | TextRole.Default                                                                                                                                                 |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Error<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table>     |

### Design

| Property               | Value                                                                                                                                                                          |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Align                  | Align.Left                                                                                                                                                                     |
| AutoHeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table>    |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                   |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                               |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                   |
| Font                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Font.'Segoe UI'<td style="background-color:#ffcccc; width:50%;">Font.'Open Sans'</td></tr></table>      |
| FontWeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">FontWeight.Semibold<td style="background-color:#ffcccc; width:50%;">FontWeight.Normal</td></tr></table> |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                                 |
| Italic                 | false                                                                                                                                                                          |
| LineHeight             | 1.2                                                                                                                                                                            |
| Overflow               | Overflow.Hidden                                                                                                                                                                |
| PaddingBottom          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                   |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                   |
| PaddingRight           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                   |
| PaddingTop             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                   |
| Size                   | 13                                                                                                                                                                             |
| Strikethrough          | false                                                                                                                                                                          |
| Underline              | false                                                                                                                                                                          |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                           |
| Visible                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayMode=DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 60<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>                 |
| X                      | 30                                                                                                                                                                             |
| Y                      | DataCardValue4.Y + DataCardValue4.Height                                                                                                                                       |
| ZIndex                 | 3                                                                                                                                                                              |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                           |
| ------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>      |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(168, 0, 0, 1)</td></tr><tr><td style="background-color:#A80000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>       |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table></td></tr></table>      |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(168, 0, 0, 1)</td></tr><tr><td style="background-color:#A80000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                 |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                 |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                |
| HoverBorderColor    | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                |
| HoverColor          | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                      |
| HoverFill           | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                       |
| PressedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                |
| PressedColor        | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                      |
| PressedFill         | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                       |

### Child & Parent Controls

| Property       | Value                 |
| -------------- | --------------------- |
| Parent Control | User\_Type\_DataCard1 |

## ErrorMessage5\_1

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property | Value                                                                                                                                                            |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Live     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Live.Assertive<td style="background-color:#ffcccc; width:50%;">Live.Off</td></tr></table> |
| Role     | TextRole.Default                                                                                                                                                 |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Error<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table>     |

### Design

| Property               | Value                                                                                                                                                                          |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Align                  | Align.Left                                                                                                                                                                     |
| AutoHeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| BorderStyle            | BorderStyle.Solid                                                                                                                                                              |
| BorderThickness        | 0                                                                                                                                                                              |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                               |
| FocusedBorderThickness | 0                                                                                                                                                                              |
| Font                   | Font.'Open Sans'                                                                                                                                                               |
| FontWeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">FontWeight.Semibold<td style="background-color:#ffcccc; width:50%;">FontWeight.Normal</td></tr></table> |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                                 |
| Italic                 | false                                                                                                                                                                          |
| LineHeight             | 1.2                                                                                                                                                                            |
| Overflow               | Overflow.Hidden                                                                                                                                                                |
| PaddingBottom          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                   |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                   |
| PaddingRight           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                   |
| PaddingTop             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                   |
| Size                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">14<td style="background-color:#ffcccc; width:50%;">13</td></tr></table>                                 |
| Strikethrough          | false                                                                                                                                                                          |
| Underline              | false                                                                                                                                                                          |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                           |
| Visible                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayMode=DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 60<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>                 |
| X                      | 30                                                                                                                                                                             |
| Y                      | Image5\_1.Y + Image5\_1.Height                                                                                                                                                 |
| ZIndex                 | 4                                                                                                                                                                              |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                      |
| ------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table> |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(168, 0, 0, 1)</td></tr><tr><td style="background-color:#A80000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>  |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table>                                                                                                                                                                                                                                                                                         |
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

| Property       | Value                |
| -------------- | -------------------- |
| Parent Control | Imagem\_DataCard1\_1 |

## Footer\_9

| Property                              | Value           |
| ------------------------------------- | --------------- |
| ![component](resources/component.png) | Type: component |

### Design

| Property | Value                                                                                                                                          |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| Height   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">40<td style="background-color:#ffcccc; width:50%;"></td></tr></table>   |
| Width    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1366<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| X        | 0                                                                                                                                              |
| Y        | 0                                                                                                                                              |
| ZIndex   | 1                                                                                                                                              |

### Color Properties

| Property | Value                                                                                                                                                                                                                                                                                                                                |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Fill     | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | cnt\_footer\_8 |

## Form1

| Property                    | Value      |
| --------------------------- | ---------- |
| ![form](resources/form.png) | Type: form |

### Behavior

| Property  | Value                                                                                                                                                                                                                                  |
| --------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnFailure | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Notify("Cannot save. Please check if there are errors in the form.", NotificationType.Error)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| OnSuccess | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">UpdateContext({ CurrentItem: Self.LastSubmit, editMode: false, newMode: false })<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |

### Data

| Property    | Value                                                                                                                                                                                                                    |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| DataSource  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Users_Info<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                     |
| DefaultMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(newMode, FormMode.New, editMode, FormMode.Edit, FormMode.View)<td style="background-color:#ffcccc; width:50%;">FormMode.Edit</td></tr></table> |
| Item        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">RecordsGallery1.Selected<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                       |

### Design

| Property        | Value                                                                                                                                       |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle     | BorderStyle.Solid                                                                                                                           |
| Height          | 500                                                                                                                                         |
| NumberOfColumns | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width           | 800                                                                                                                                         |
| X               | 0                                                                                                                                           |
| Y               | 0                                                                                                                                           |
| ZIndex          | 23                                                                                                                                          |

### Color Properties

| Property           | Value                                                                                                                                                                                                                                                                                                                                                                                                            |
| ------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(245, 245, 245, 1)</td></tr><tr><td style="background-color:#F5F5F5"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table> |
| Fill               | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                  |
| FocusedBorderColor | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                 |

### Child & Parent Controls

| Property       | Value                 |
| -------------- | --------------------- |
| Child Control  | Username\_DataCard1   |
| Child Control  | Passwords\_DataCard1  |
| Child Control  | User\_Type\_DataCard1 |
| Parent Control | MainContainer1        |

## Form1\_1

| Property                    | Value      |
| --------------------------- | ---------- |
| ![form](resources/form.png) | Type: form |

### Behavior

| Property  | Value                                                                                                                                                                                                                                  |
| --------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnFailure | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Notify("Cannot save. Please check if there are errors in the form.", NotificationType.Error)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| OnSuccess | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">UpdateContext({ CurrentItem: Self.LastSubmit, editMode: false, newMode: false })<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |

### Data

| Property    | Value                                                                                                                                                                                                                    |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| DataSource  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Users_Info<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                     |
| DefaultMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(newMode, FormMode.New, editMode, FormMode.Edit, FormMode.View)<td style="background-color:#ffcccc; width:50%;">FormMode.Edit</td></tr></table> |
| Item        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">RecordsGallery1.Selected<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                       |

### Design

| Property        | Value                                                                                                                                       |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle     | BorderStyle.Solid                                                                                                                           |
| Height          | 500                                                                                                                                         |
| NumberOfColumns | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width           | 800                                                                                                                                         |
| X               | 0                                                                                                                                           |
| Y               | 0                                                                                                                                           |
| ZIndex          | 24                                                                                                                                          |

### Color Properties

| Property           | Value                                                                                                                                                                                                                                                                                                                                                                                                            |
| ------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(245, 245, 245, 1)</td></tr><tr><td style="background-color:#F5F5F5"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table> |
| Fill               | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                  |
| FocusedBorderColor | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                 |

### Child & Parent Controls

| Property       | Value                |
| -------------- | -------------------- |
| Child Control  | Imagem\_DataCard1\_1 |
| Child Control  | Name\_DataCard1\_1   |
| Parent Control | MainContainer1       |

## galleryTemplate1\_1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![galleryTemplate](resources/galleryTemplate.png) | Type: galleryTemplate |

### Behavior

| Property | Value                                                                                                                                                                                                  |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">UpdateContext({ itemSelected: true, CurrentItem: ThisItem })<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                                                   |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| TemplateFill | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Self.IsSelected, RGBA(230, 230, 230, 1), RGBA(0, 0, 0, 0))<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Color Properties

### Child & Parent Controls

| Property       | Value           |
| -------------- | --------------- |
| Parent Control | RecordsGallery1 |

## Header\_9

| Property                              | Value           |
| ------------------------------------- | --------------- |
| ![component](resources/component.png) | Type: component |

### Design

| Property | Value                                                                                                                                                   |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Height   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1366<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| X        | 0                                                                                                                                                       |
| Y        | 0                                                                                                                                                       |
| ZIndex   | 1                                                                                                                                                       |

### Color Properties

| Property | Value                                                                                                                                                                                                                                                                                                                                |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Fill     | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | cnt\_header\_8 |

## Image5\_1

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![image](resources/image.png) | Type: image |

### Data

| Property | Value                                                                                                                                                                                                                      |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Image    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(IsBlank(AddPicture1_1.Media), Parent.Default, AddPicture1_1.Media)<td style="background-color:#ffcccc; width:50%;">SampleImage</td></tr></table> |
| Tooltip  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayName<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                               |

### Design

| Property               | Value                                                                                                                                                                        |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle            | BorderStyle.Solid                                                                                                                                                            |
| BorderThickness        | 0                                                                                                                                                                            |
| DisplayMode            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayMode<td style="background-color:#ffcccc; width:50%;">DisplayMode.Edit</td></tr></table> |
| FocusedBorderThickness | 2                                                                                                                                                                            |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">AddPicture1_1.Height<td style="background-color:#ffcccc; width:50%;">100</td></tr></table>            |
| ImagePosition          | ImagePosition.Fit                                                                                                                                                            |
| ImageRotation          | ImageRotation.None                                                                                                                                                           |
| PaddingBottom          | 0                                                                                                                                                                            |
| PaddingLeft            | 0                                                                                                                                                                            |
| PaddingRight           | 0                                                                                                                                                                            |
| PaddingTop             | 0                                                                                                                                                                            |
| RadiusBottomLeft       | 0                                                                                                                                                                            |
| RadiusBottomRight      | 0                                                                                                                                                                            |
| RadiusTopLeft          | 0                                                                                                                                                                            |
| RadiusTopRight         | 0                                                                                                                                                                            |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">AddPicture1_1.Width<td style="background-color:#ffcccc; width:50%;">100</td></tr></table>             |
| X                      | AddPicture1\_1.X                                                                                                                                                             |
| Y                      | AddPicture1\_1.Y                                                                                                                                                             |
| ZIndex                 | 2                                                                                                                                                                            |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | If(IsBlank(Parent.Error), Parent.BorderColor, Color.Red)                                                              |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| FocusedBorderColor  | Self.BorderColor                                                                                                      |
| HoverBorderColor    | ColorFade(Self.BorderColor, 20%)                                                                                      |
| HoverFill           | ColorFade(Self.Fill, 20%)                                                                                             |
| PressedBorderColor  | ColorFade(Self.BorderColor, \-20%)                                                                                    |
| PressedFill         | ColorFade(Self.Fill, \-20%)                                                                                           |

### Child & Parent Controls

| Property       | Value                |
| -------------- | -------------------- |
| Parent Control | Imagem\_DataCard1\_1 |

## Imagem\_DataCard1\_1

| Property                                      | Value               |
| --------------------------------------------- | ------------------- |
| ![typedDataCard](resources/typedDataCard.png) | Type: typedDataCard |

### Data

| Property    | Value                                                                                                                                                                                                             |
| ----------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DataField   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"crfe1_imagem"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                          |
| Default     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.Imagem<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                         |
| DisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataSourceInfo([@Users_Info],DataSourceInfo.DisplayName,"crfe1_imagem")<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Required    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                   |
| Update      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Image5_1.Image<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                          |

### Design

| Property    | Value                                                                                                                                                        |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderStyle | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayMode<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">215<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">434<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| X           | 0                                                                                                                                                            |
| Y           | 0                                                                                                                                                            |
| ZIndex      | 1                                                                                                                                                            |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                   |
| ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>    |

### Child & Parent Controls

| Property       | Value            |
| -------------- | ---------------- |
| Child Control  | Image5\_1        |
| Child Control  | AddPicture1\_1   |
| Child Control  | StarVisible5\_1  |
| Child Control  | DataCardKey5\_1  |
| Child Control  | ErrorMessage5\_1 |
| Parent Control | Form1\_1         |

## MainContainer1

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
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">200<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Horizontal<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">500<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| X                    | 0                                                                                                                                                                    |
| Y                    | 0                                                                                                                                                                    |
| ZIndex               | 22                                                                                                                                                                   |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                      |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value           |
| -------------- | --------------- |
| Child Control  | Form1           |
| Child Control  | Form1\_1        |
| Parent Control | RightContainer1 |

## Name\_DataCard1\_1

| Property                                      | Value               |
| --------------------------------------------- | ------------------- |
| ![typedDataCard](resources/typedDataCard.png) | Type: typedDataCard |

### Data

| Property    | Value                                                                                                                                                                                                               |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DataField   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"crfe1_username"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                          |
| Default     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.Name<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                             |
| DisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataSourceInfo([@Users_Info],DataSourceInfo.DisplayName,"crfe1_username")<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| MaxLength   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataSourceInfo([@Users_Info], DataSourceInfo.MaxLength, "crfe1_username")<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Required    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                      |
| Update      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataCardValue1_1.Text<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                     |

### Design

| Property    | Value                                                                                                                                                        |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderStyle | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayMode<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">50<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">458<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| X           | 0                                                                                                                                                            |
| Y           | 1                                                                                                                                                            |
| ZIndex      | 24                                                                                                                                                           |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                      |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(245, 245, 245, 1)</td></tr><tr><td style="background-color:#F5F5F5"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |

### Child & Parent Controls

| Property       | Value             |
| -------------- | ----------------- |
| Child Control  | DataCardValue1\_1 |
| Child Control  | StarVisible1\_1   |
| Child Control  | DataCardKey1\_1   |
| Child Control  | ErrorMessage1\_1  |
| Parent Control | Form1\_1          |

## NewRecordAddIcon1

| Property                    | Value      |
| --------------------------- | ---------- |
| ![icon](resources/icon.png) | Type: icon |

### Behavior

| Property | Value                                                                                                                                                                                       |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">NewForm(Form1); UpdateContext({ newMode: true });<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property               | Value                                                                                                                                                       |
| ---------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| DisplayMode            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">44<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Icon                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Icon.Add<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| PaddingBottom          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| PaddingRight           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| PaddingTop             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">44<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| X                      | 0                                                                                                                                                           |
| Y                      | 0                                                                                                                                                           |
| ZIndex                 | 10                                                                                                                                                          |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                      |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(252, 65, 123, 1)</td></tr><tr><td style="background-color:#FC417B"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>  |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(245, 245, 245, 1)</td></tr><tr><td style="background-color:#F5F5F5"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(225, 223, 221, 1)</td></tr><tr><td style="background-color:#E1DFDD"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| Fill                | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                           |
| HoverBorderColor    | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| HoverColor          | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(16, 110, 190, 1)</td></tr><tr><td style="background-color:#106EBE"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>  |
| HoverFill           | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| PressedBorderColor  | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| PressedColor        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(16, 110, 190, 1)</td></tr><tr><td style="background-color:#106EBE"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>  |
| PressedFill         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |

### Child & Parent Controls

| Property       | Value                        |
| -------------- | ---------------------------- |
| Parent Control | NewRecordButtonBarContainer1 |

## NewRecordButtonBarContainer1

| Property                                                                      | Value                               |
| ----------------------------------------------------------------------------- | ----------------------------------- |
| ![horizontalAutoLayoutContainer](resources/horizontalAutoLayoutContainer.png) | Type: horizontalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.None<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">44<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Horizontal<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">500<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| X                    | 0                                                                                                                                                                    |
| Y                    | 0                                                                                                                                                                    |
| ZIndex               | 9                                                                                                                                                                    |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value             |
| -------------- | ----------------- |
| Child Control  | NewRecordAddIcon1 |
| Child Control  | NewRecordLabel1   |
| Parent Control | SidebarContainer1 |

## NewRecordLabel1

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property | Value                                                                                                                                                 |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| Live     | Live.Off                                                                                                                                              |
| Role     | TextRole.Default                                                                                                                                      |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"New"<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |

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
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">44<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                              |
| Italic                 | false                                                                                                                                                                       |
| LineHeight             | 1.2                                                                                                                                                                         |
| Overflow               | Overflow.Hidden                                                                                                                                                             |
| PaddingBottom          | 5                                                                                                                                                                           |
| PaddingLeft            | 5                                                                                                                                                                           |
| PaddingRight           | 5                                                                                                                                                                           |
| PaddingTop             | 5                                                                                                                                                                           |
| Size                   | 13                                                                                                                                                                          |
| Strikethrough          | false                                                                                                                                                                       |
| Underline              | false                                                                                                                                                                       |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                        |
| Width                  | 150                                                                                                                                                                         |
| X                      | 0                                                                                                                                                                           |
| Y                      | 0                                                                                                                                                                           |
| ZIndex                 | 11                                                                                                                                                                          |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>          |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(50, 49, 48, 1)</td></tr><tr><td style="background-color:#323130"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>          |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table></td></tr></table>          |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(161, 159, 157, 1)</td></tr><tr><td style="background-color:#A19F9D"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                     |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                     |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverBorderColor    | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverColor          | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                          |
| HoverFill           | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                           |
| PressedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| PressedColor        | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                          |
| PressedFill         | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                           |

### Child & Parent Controls

| Property       | Value                        |
| -------------- | ---------------------------- |
| Parent Control | NewRecordButtonBarContainer1 |

## NextArrow1

| Property                    | Value      |
| --------------------------- | ---------- |
| ![icon](resources/icon.png) | Type: icon |

### Behavior

| Property | Value                                                                                                                                                    |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Select(Parent)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property        | Value                                                                                                                                                         |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| AccessibleLabel | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Self.Tooltip<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| Tooltip         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"View item details"<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property               | Value                                                                                                                                                       |
| ---------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| DisplayMode            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">50<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Icon                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Icon.ChevronRight<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| PaddingBottom          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| PaddingRight           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| PaddingTop             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| TabIndex               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">-1<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">50<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| X                      | Parent.TemplateWidth \- Self.Width \- 12                                                                                                                    |
| Y                      | (Parent.TemplateHeight \/ 2) \- (Self.Height \/ 2)                                                                                                          |
| ZIndex                 | 4                                                                                                                                                           |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                      |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(29, 157, 255, 1)</td></tr><tr><td style="background-color:#1D9DFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>  |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(245, 245, 245, 1)</td></tr><tr><td style="background-color:#F5F5F5"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(225, 223, 221, 1)</td></tr><tr><td style="background-color:#E1DFDD"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| Fill                | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                           |
| HoverBorderColor    | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| HoverColor          | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(16, 110, 190, 1)</td></tr><tr><td style="background-color:#106EBE"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>  |
| HoverFill           | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| PressedBorderColor  | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| PressedColor        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(16, 110, 190, 1)</td></tr><tr><td style="background-color:#106EBE"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>  |
| PressedFill         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |

### Child & Parent Controls

| Property       | Value           |
| -------------- | --------------- |
| Parent Control | RecordsGallery1 |

## Passwords\_DataCard1

| Property                                      | Value               |
| --------------------------------------------- | ------------------- |
| ![typedDataCard](resources/typedDataCard.png) | Type: typedDataCard |

### Data

| Property    | Value                                                                                                                                                                                                                |
| ----------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DataField   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"crfe1_passwords"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                          |
| Default     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.Passwords<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                         |
| DisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataSourceInfo([@Users_Info],DataSourceInfo.DisplayName,"crfe1_passwords")<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| MaxLength   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataSourceInfo([@Users_Info], DataSourceInfo.MaxLength, "crfe1_passwords")<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Required    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                       |
| Update      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataCardValue3.Text<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                        |

### Design

| Property    | Value                                                                                                                                                        |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderStyle | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayMode<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">50<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">458<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| X           | 0                                                                                                                                                            |
| Y           | 1                                                                                                                                                            |
| ZIndex      | 24                                                                                                                                                           |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                      |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(245, 245, 245, 1)</td></tr><tr><td style="background-color:#F5F5F5"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Child Control  | StarVisible3   |
| Child Control  | DataCardKey3   |
| Child Control  | DataCardValue3 |
| Child Control  | ErrorMessage3  |
| Parent Control | Form1          |

## RecordsGallery1

| Property                          | Value         |
| --------------------------------- | ------------- |
| ![gallery](resources/gallery.png) | Type: gallery |

### Data

| Property  | Value                                                                                                                                                                                                                                                                        |
| --------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Default   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">CurrentItem<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                                        |
| Items     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Search([@Users_Info], SearchInput1.Text, "crfe1_username", "crfe1_password","crfe1_passwords","crfe1_username")<td style="background-color:#ffcccc; width:50%;">CustomGallerySample</td></tr></table> |
| WrapCount | 1                                                                                                                                                                                                                                                                            |

### Design

| Property            | Value                                                                                                                                                                            |
| ------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle         | BorderStyle.Solid                                                                                                                                                                |
| DelayItemLoading    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                   |
| DisplayMode         | DisplayMode.Edit                                                                                                                                                                 |
| Height              | 575                                                                                                                                                                              |
| Layout              | Layout.Vertical                                                                                                                                                                  |
| LoadingSpinner      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LoadingSpinner.Data<td style="background-color:#ffcccc; width:50%;">LoadingSpinner.None</td></tr></table> |
| LoadingSpinnerColor | Self.BorderColor                                                                                                                                                                 |
| TemplatePadding     | 0                                                                                                                                                                                |
| TemplateSize        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">104<td style="background-color:#ffcccc; width:50%;">Min(160, Self.Height - 60)</td></tr></table>          |
| Transition          | Transition.None                                                                                                                                                                  |
| Width               | 640                                                                                                                                                                              |
| X                   | 0                                                                                                                                                                                |
| Y                   | 0                                                                                                                                                                                |
| ZIndex              | 13                                                                                                                                                                               |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                            |
| ------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(245, 245, 245, 1)</td></tr><tr><td style="background-color:#F5F5F5"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table> |
| DisabledBorderColor | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                 |
| DisabledFill        | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                        |
| Fill                | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(250, 250, 250, 1)</td></tr><tr><td style="background-color:#FAFAFA"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>    |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                 |
| HoverBorderColor    | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                 |
| HoverFill           | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                        |
| PressedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                 |
| PressedFill         | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                        |

### Child & Parent Controls

| Property       | Value               |
| -------------- | ------------------- |
| Child Control  | galleryTemplate1\_1 |
| Child Control  | Rectangle1          |
| Child Control  | Title1\_1           |
| Child Control  | NextArrow1          |
| Child Control  | Subtitle1\_1        |
| Child Control  | Body1               |
| Child Control  | Separator1          |
| Parent Control | SidebarContainer1   |

## RecordsListSeparator1

| Property                              | Value           |
| ------------------------------------- | --------------- |
| ![rectangle](resources/rectangle.png) | Type: rectangle |

### Design

| Property               | Value                                                                                                                                                      |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| DisplayMode            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">150<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| X                      | 0                                                                                                                                                          |
| Y                      | 0                                                                                                                                                          |
| ZIndex                 | 12                                                                                                                                                         |

### Color Properties

| Property           | Value                                                                                                                                                                                                                                                                                                                                      |
| ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| DisabledFill       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(161, 159, 157, 1)</td></tr><tr><td style="background-color:#A19F9D"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(225, 223, 221, 1)</td></tr><tr><td style="background-color:#E1DFDD"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| FocusedBorderColor | Self.BorderColor                                                                                                                                                                                                                                                                                                                           |
| HoverFill          | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 120, 212, 1)</td></tr><tr><td style="background-color:#0078D4"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>   |
| PressedFill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 120, 212, 1)</td></tr><tr><td style="background-color:#0078D4"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>   |

### Child & Parent Controls

| Property       | Value             |
| -------------- | ----------------- |
| Parent Control | SidebarContainer1 |

## Rectangle1

| Property                              | Value           |
| ------------------------------------- | --------------- |
| ![rectangle](resources/rectangle.png) | Type: rectangle |

### Behavior

| Property | Value                                                                                                                                                    |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Select(Parent)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property        | Value                                                                                                                                                                               |
| --------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| BorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                         |
| DisplayMode     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| Height          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.TemplateHeight - Separator1.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| TabIndex        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">-1<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                        |
| Visible         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.IsSelected<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| Width           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                         |
| X               | 0                                                                                                                                                                                   |
| Y               | 0                                                                                                                                                                                   |
| ZIndex          | 6                                                                                                                                                                                   |

### Color Properties

| Property           | Value                                                                                                                                                                                                                                                                                                                                     |
| ------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>      |
| DisabledFill       | Self.Fill                                                                                                                                                                                                                                                                                                                                 |
| Fill               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(29, 157, 255, 1)</td></tr><tr><td style="background-color:#1D9DFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| FocusedBorderColor | Self.BorderColor                                                                                                                                                                                                                                                                                                                          |
| HoverFill          | Self.Fill                                                                                                                                                                                                                                                                                                                                 |
| PressedFill        | Self.Fill                                                                                                                                                                                                                                                                                                                                 |

### Child & Parent Controls

| Property       | Value           |
| -------------- | --------------- |
| Parent Control | RecordsGallery1 |

## ResetFormButton1

| Property                    | Value      |
| --------------------------- | ---------- |
| ![icon](resources/icon.png) | Type: icon |

### Behavior

| Property | Value                                                                                                                                                                                                           |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ResetForm(Form1); UpdateContext({ editMode: false, newMode: false });<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property               | Value                                                                                                                                                           |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                     |
| DisplayMode            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                     |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">50<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| Icon                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Icon.Cancel<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| PaddingBottom          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">12<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">12<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| PaddingRight           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">12<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| PaddingTop             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">12<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| TabIndex               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                     |
| Visible                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Or(editMode, newMode)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">50<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| X                      | 0                                                                                                                                                               |
| Y                      | 0                                                                                                                                                               |
| ZIndex                 | 19                                                                                                                                                              |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                      |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 120, 212, 1)</td></tr><tr><td style="background-color:#0078D4"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>   |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(245, 245, 245, 1)</td></tr><tr><td style="background-color:#F5F5F5"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(225, 223, 221, 1)</td></tr><tr><td style="background-color:#E1DFDD"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| Fill                | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                           |
| HoverBorderColor    | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| HoverColor          | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(16, 110, 190, 1)</td></tr><tr><td style="background-color:#106EBE"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>  |
| HoverFill           | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| PressedBorderColor  | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| PressedColor        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(16, 110, 190, 1)</td></tr><tr><td style="background-color:#106EBE"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>  |
| PressedFill         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |

### Child & Parent Controls

| Property       | Value                          |
| -------------- | ------------------------------ |
| Parent Control | SelectedRecordHeaderContainer1 |

## RightContainer1

| Property                                                                  | Value                             |
| ------------------------------------------------------------------------- | --------------------------------- |
| ![verticalAutoLayoutContainer](resources/verticalAutoLayoutContainer.png) | Type: verticalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                                                                                                       |
| -------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                 |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                              |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                  |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.None<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                   |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">200<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                               |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Stretch<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                          |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Vertical<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                          |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                                |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                        |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                   |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                               |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                               |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                             |
| PaddingBottom        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                                 |
| PaddingLeft          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                                 |
| PaddingRight         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                                 |
| PaddingTop           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                                 |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                                 |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                                 |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                                 |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                                 |
| Visible              | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Or(deleteMode, And(BodyContainer1.Width = ScreenSize.Small, !newMode, !editMode, !itemSelected)), false, true)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                                 |
| X                    | 0                                                                                                                                                                                                                                                           |
| Y                    | 0                                                                                                                                                                                                                                                           |
| ZIndex               | 14                                                                                                                                                                                                                                                          |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value                          |
| -------------- | ------------------------------ |
| Child Control  | SelectedRecordHeaderContainer1 |
| Child Control  | MainContainer1                 |
| Parent Control | BodyContainer1                 |

## ScreenContainer1

| Property                                                                  | Value                             |
| ------------------------------------------------------------------------- | --------------------------------- |
| ![verticalAutoLayoutContainer](resources/verticalAutoLayoutContainer.png) | Type: verticalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.None<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Stretch<td style="background-color:#ffcccc; width:50%;"></td></tr></table>   |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Vertical<td style="background-color:#ffcccc; width:50%;"></td></tr></table>   |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">15<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| PaddingBottom        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| PaddingLeft          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| PaddingRight         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| PaddingTop           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| X                    | 0                                                                                                                                                                    |
| Y                    | 0                                                                                                                                                                    |
| ZIndex               | 1                                                                                                                                                                    |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                      |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(250, 250, 250, 1)</td></tr><tr><td style="background-color:#FAFAFA"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value               |
| -------------- | ------------------- |
| Child Control  | TableNameContainer1 |
| Child Control  | BodyContainer1      |
| Parent Control | Container1          |

## SearchContainer1

| Property                                                                      | Value                               |
| ----------------------------------------------------------------------------- | ----------------------------------- |
| ![horizontalAutoLayoutContainer](resources/horizontalAutoLayoutContainer.png) | Type: horizontalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.None<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">44<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Horizontal<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">500<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| X                    | 0                                                                                                                                                                    |
| Y                    | 0                                                                                                                                                                    |
| ZIndex               | 6                                                                                                                                                                    |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                      |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(245, 245, 245, 1)</td></tr><tr><td style="background-color:#F5F5F5"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value             |
| -------------- | ----------------- |
| Child Control  | SearchInput1      |
| Child Control  | SearchIcon1       |
| Parent Control | SidebarContainer1 |

## SearchIcon1

| Property                    | Value      |
| --------------------------- | ---------- |
| ![icon](resources/icon.png) | Type: icon |

### Data

| Property | Value                                                                                                                                              |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tooltip  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Search"<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property      | Value                                                                                                                                                       |
| ------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| DisplayMode   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| Height        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">44<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Icon          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Icon.Search<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |
| PaddingBottom | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| PaddingLeft   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| PaddingRight  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| PaddingTop    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Width         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">44<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| X             | 0                                                                                                                                                           |
| Y             | 0                                                                                                                                                           |
| ZIndex        | 8                                                                                                                                                           |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                      |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(252, 65, 123, 1)</td></tr><tr><td style="background-color:#FC417B"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>  |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>    |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(119, 119, 119, 1)</td></tr><tr><td style="background-color:#777777"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
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

| Property       | Value            |
| -------------- | ---------------- |
| Parent Control | SearchContainer1 |

## SearchInput1

| Property                    | Value      |
| --------------------------- | ---------- |
| ![text](resources/text.png) | Type: text |

### Data

| Property    | Value                                                                                                                                                    |
| ----------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Default     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;">"Text input"</td></tr></table> |
| DelayOutput | false                                                                                                                                                    |
| HintText    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Search"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |

### Design

| Property            | Value                                                                                                                                                                       |
| ------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align               | Align.Left                                                                                                                                                                  |
| BorderStyle         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table> |
| DisplayMode         | DisplayMode.Edit                                                                                                                                                            |
| Font                | Font.'Open Sans'                                                                                                                                                            |
| FontWeight          | FontWeight.Normal                                                                                                                                                           |
| Format              | TextFormat.Text                                                                                                                                                             |
| Height              | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">44<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                              |
| Mode                | TextMode.SingleLine                                                                                                                                                         |
| VirtualKeyboardMode | VirtualKeyboardMode.Auto                                                                                                                                                    |
| Width               | 320                                                                                                                                                                         |
| X                   | 0                                                                                                                                                                           |
| Y                   | 0                                                                                                                                                                           |
| ZIndex              | 7                                                                                                                                                                           |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                         |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>    |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(70, 68, 64, 1)</td></tr><tr><td style="background-color:#464440"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>    |
| DisabledBorderColor | ColorFade(Self.BorderColor, 40%)                                                                                                                                                                                                                                                                                                                                                                              |
| DisabledColor       | ColorFade(Self.Color, 40%)                                                                                                                                                                                                                                                                                                                                                                                    |
| DisabledFill        | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                     |
| Fill                | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td></tr></table> |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                              |
| HoverBorderColor    | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverColor          | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverFill           | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(186, 202, 226, 1)</td></tr><tr><td style="background-color:#BACAE2"></td></tr></table></td></tr></table> |
| PressedBorderColor  | Self.HoverBorderColor                                                                                                                                                                                                                                                                                                                                                                                         |
| PressedColor        | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                    |
| PressedFill         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.Fill</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>              |

### Child & Parent Controls

| Property       | Value            |
| -------------- | ---------------- |
| Parent Control | SearchContainer1 |

## SelectedRecordHeaderContainer1

| Property                                                                      | Value                               |
| ----------------------------------------------------------------------------- | ----------------------------------- |
| ![horizontalAutoLayoutContainer](resources/horizontalAutoLayoutContainer.png) | Type: horizontalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.Light<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">50<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Center<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Horizontal<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">500<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| X                    | 0                                                                                                                                                                    |
| Y                    | 0                                                                                                                                                                    |
| ZIndex               | 15                                                                                                                                                                   |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                      |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value                |
| -------------- | -------------------- |
| Child Control  | BackIconButton1      |
| Child Control  | SelectedRecordTitle1 |
| Child Control  | SubmitFormButton1    |
| Child Control  | ResetFormButton1     |
| Child Control  | EditIconButton1      |
| Child Control  | DeleteIconButton1    |
| Parent Control | RightContainer1      |

## SelectedRecordTitle1

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property | Value                                                                                                                                                                         |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Live     | Live.Off                                                                                                                                                                      |
| Role     | TextRole.Default                                                                                                                                                              |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">RecordsGallery1.Selected.Name<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |

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
| Height                 | 40                                                                                                                                                                             |
| Italic                 | false                                                                                                                                                                          |
| LineHeight             | 1.2                                                                                                                                                                            |
| Overflow               | Overflow.Hidden                                                                                                                                                                |
| PaddingBottom          | 5                                                                                                                                                                              |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                  |
| PaddingRight           | 5                                                                                                                                                                              |
| PaddingTop             | 5                                                                                                                                                                              |
| Size                   | 13                                                                                                                                                                             |
| Strikethrough          | false                                                                                                                                                                          |
| Underline              | false                                                                                                                                                                          |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                           |
| Width                  | 150                                                                                                                                                                            |
| X                      | 0                                                                                                                                                                              |
| Y                      | 0                                                                                                                                                                              |
| ZIndex                 | 17                                                                                                                                                                             |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>          |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(50, 49, 48, 1)</td></tr><tr><td style="background-color:#323130"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>          |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table></td></tr></table>          |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(161, 159, 157, 1)</td></tr><tr><td style="background-color:#A19F9D"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                     |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                     |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverBorderColor    | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverColor          | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                          |
| HoverFill           | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                           |
| PressedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| PressedColor        | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                          |
| PressedFill         | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                           |

### Child & Parent Controls

| Property       | Value                          |
| -------------- | ------------------------------ |
| Parent Control | SelectedRecordHeaderContainer1 |

## Separator1

| Property                              | Value           |
| ------------------------------------- | --------------- |
| ![rectangle](resources/rectangle.png) | Type: rectangle |

### Behavior

| Property | Value                                                                                                                                                    |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Select(Parent)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property        | Value                                                                                                                                                          |
| --------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| BorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| DisplayMode     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| Height          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">8<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| TabIndex        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">-1<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                   |
| Width           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.TemplateWidth<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| X               | 0                                                                                                                                                              |
| Y               | Parent.TemplateHeight \- Self.Height                                                                                                                           |
| ZIndex          | 5                                                                                                                                                              |

### Color Properties

| Property           | Value                                                                                                                                                                                                                                                                                                                                      |
| ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| DisabledFill       | Self.Fill                                                                                                                                                                                                                                                                                                                                  |
| Fill               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| FocusedBorderColor | Self.BorderColor                                                                                                                                                                                                                                                                                                                           |
| HoverFill          | Self.Fill                                                                                                                                                                                                                                                                                                                                  |
| PressedFill        | Self.Fill                                                                                                                                                                                                                                                                                                                                  |

### Child & Parent Controls

| Property       | Value           |
| -------------- | --------------- |
| Parent Control | RecordsGallery1 |

## SidebarContainer1

| Property                                                                  | Value                             |
| ------------------------------------------------------------------------- | --------------------------------- |
| ![verticalAutoLayoutContainer](resources/verticalAutoLayoutContainer.png) | Type: verticalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                                                                                        |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                  |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                               |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                   |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.Light<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                   |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">200<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                             |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Vertical<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                           |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                 |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                         |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                    |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                              |
| PaddingLeft          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                 |
| PaddingRight         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                 |
| PaddingTop           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                 |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                 |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                 |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                 |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                 |
| Visible              | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(And(BodyContainer1.Width = ScreenSize.Small, Or(newMode, editMode, itemSelected)), false, true)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">500<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                |
| X                    | 0                                                                                                                                                                                                                                            |
| Y                    | 0                                                                                                                                                                                                                                            |
| ZIndex               | 5                                                                                                                                                                                                                                            |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                      |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value                        |
| -------------- | ---------------------------- |
| Child Control  | SearchContainer1             |
| Child Control  | NewRecordButtonBarContainer1 |
| Child Control  | RecordsListSeparator1        |
| Child Control  | RecordsGallery1              |
| Parent Control | BodyContainer1               |

## StarVisible1\_1

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property | Value                                                                                                                                               |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| Live     | Live.Off                                                                                                                                            |
| Role     | TextRole.Default                                                                                                                                    |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"*"<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                                               |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Align.Center<td style="background-color:#ffcccc; width:50%;">Align.Left</td></tr></table>                                    |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table>                         |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                                        |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                                                    |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                                        |
| Font                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Font.'Segoe UI'<td style="background-color:#ffcccc; width:50%;">Font.'Open Sans'</td></tr></table>                           |
| FontWeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">FontWeight.Semibold<td style="background-color:#ffcccc; width:50%;">FontWeight.Normal</td></tr></table>                      |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataCardKey1_1.Height<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                                   |
| Italic                 | false                                                                                                                                                                                               |
| LineHeight             | 1.2                                                                                                                                                                                                 |
| Overflow               | Overflow.Hidden                                                                                                                                                                                     |
| PaddingBottom          | 5                                                                                                                                                                                                   |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                                        |
| PaddingRight           | 5                                                                                                                                                                                                   |
| PaddingTop             | 5                                                                                                                                                                                                   |
| Size                   | 13                                                                                                                                                                                                  |
| Strikethrough          | false                                                                                                                                                                                               |
| Underline              | false                                                                                                                                                                                               |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                                                |
| Visible                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">And(Parent.Required, Parent.DisplayMode=DisplayMode.Edit)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>                                                     |
| Wrap                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                     |
| X                      | 0                                                                                                                                                                                                   |
| Y                      | DataCardKey1\_1.Y                                                                                                                                                                                   |
| ZIndex                 | 4                                                                                                                                                                                                   |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>          |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(50, 49, 48, 1)</td></tr><tr><td style="background-color:#323130"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>          |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table></td></tr></table>          |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(161, 159, 157, 1)</td></tr><tr><td style="background-color:#A19F9D"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                     |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                     |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverBorderColor    | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverColor          | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                          |
| HoverFill           | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                           |
| PressedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| PressedColor        | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                          |
| PressedFill         | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                           |

### Child & Parent Controls

| Property       | Value              |
| -------------- | ------------------ |
| Parent Control | Name\_DataCard1\_1 |

## StarVisible2

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property | Value                                                                                                                                               |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| Live     | Live.Off                                                                                                                                            |
| Role     | TextRole.Default                                                                                                                                    |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"*"<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                                               |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Align.Center<td style="background-color:#ffcccc; width:50%;">Align.Left</td></tr></table>                                    |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table>                         |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                                        |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                                                    |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                                        |
| Font                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Font.'Segoe UI'<td style="background-color:#ffcccc; width:50%;">Font.'Open Sans'</td></tr></table>                           |
| FontWeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">FontWeight.Semibold<td style="background-color:#ffcccc; width:50%;">FontWeight.Normal</td></tr></table>                      |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataCardKey2.Height<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                                     |
| Italic                 | false                                                                                                                                                                                               |
| LineHeight             | 1.2                                                                                                                                                                                                 |
| Overflow               | Overflow.Hidden                                                                                                                                                                                     |
| PaddingBottom          | 5                                                                                                                                                                                                   |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                                        |
| PaddingRight           | 5                                                                                                                                                                                                   |
| PaddingTop             | 5                                                                                                                                                                                                   |
| Size                   | 13                                                                                                                                                                                                  |
| Strikethrough          | false                                                                                                                                                                                               |
| Underline              | false                                                                                                                                                                                               |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                                                |
| Visible                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">And(Parent.Required, Parent.DisplayMode=DisplayMode.Edit)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>                                                     |
| Wrap                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                     |
| X                      | 0                                                                                                                                                                                                   |
| Y                      | DataCardKey2.Y                                                                                                                                                                                      |
| ZIndex                 | 4                                                                                                                                                                                                   |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>          |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(50, 49, 48, 1)</td></tr><tr><td style="background-color:#323130"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>          |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table></td></tr></table>          |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(161, 159, 157, 1)</td></tr><tr><td style="background-color:#A19F9D"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                     |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                     |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverBorderColor    | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverColor          | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                          |
| HoverFill           | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                           |
| PressedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| PressedColor        | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                          |
| PressedFill         | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                           |

### Child & Parent Controls

| Property       | Value               |
| -------------- | ------------------- |
| Parent Control | Username\_DataCard1 |

## StarVisible3

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property | Value                                                                                                                                               |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| Live     | Live.Off                                                                                                                                            |
| Role     | TextRole.Default                                                                                                                                    |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"*"<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                                               |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Align.Center<td style="background-color:#ffcccc; width:50%;">Align.Left</td></tr></table>                                    |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table>                         |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                                        |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                                                    |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                                        |
| Font                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Font.'Segoe UI'<td style="background-color:#ffcccc; width:50%;">Font.'Open Sans'</td></tr></table>                           |
| FontWeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">FontWeight.Semibold<td style="background-color:#ffcccc; width:50%;">FontWeight.Normal</td></tr></table>                      |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataCardKey3.Height<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                                     |
| Italic                 | false                                                                                                                                                                                               |
| LineHeight             | 1.2                                                                                                                                                                                                 |
| Overflow               | Overflow.Hidden                                                                                                                                                                                     |
| PaddingBottom          | 5                                                                                                                                                                                                   |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                                        |
| PaddingRight           | 5                                                                                                                                                                                                   |
| PaddingTop             | 5                                                                                                                                                                                                   |
| Size                   | 13                                                                                                                                                                                                  |
| Strikethrough          | false                                                                                                                                                                                               |
| Underline              | false                                                                                                                                                                                               |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                                                |
| Visible                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">And(Parent.Required, Parent.DisplayMode=DisplayMode.Edit)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>                                                     |
| Wrap                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                     |
| X                      | 0                                                                                                                                                                                                   |
| Y                      | DataCardKey3.Y                                                                                                                                                                                      |
| ZIndex                 | 4                                                                                                                                                                                                   |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>          |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(50, 49, 48, 1)</td></tr><tr><td style="background-color:#323130"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>          |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table></td></tr></table>          |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(161, 159, 157, 1)</td></tr><tr><td style="background-color:#A19F9D"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                     |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                     |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverBorderColor    | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverColor          | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                          |
| HoverFill           | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                           |
| PressedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| PressedColor        | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                          |
| PressedFill         | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                           |

### Child & Parent Controls

| Property       | Value                |
| -------------- | -------------------- |
| Parent Control | Passwords\_DataCard1 |

## StarVisible4

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property | Value                                                                                                                                               |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| Live     | Live.Off                                                                                                                                            |
| Role     | TextRole.Default                                                                                                                                    |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"*"<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                                               |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Align.Center<td style="background-color:#ffcccc; width:50%;">Align.Left</td></tr></table>                                    |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table>                         |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                                        |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                                                    |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                                        |
| Font                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Font.'Segoe UI'<td style="background-color:#ffcccc; width:50%;">Font.'Open Sans'</td></tr></table>                           |
| FontWeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">FontWeight.Semibold<td style="background-color:#ffcccc; width:50%;">FontWeight.Normal</td></tr></table>                      |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataCardKey4.Height<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                                     |
| Italic                 | false                                                                                                                                                                                               |
| LineHeight             | 1.2                                                                                                                                                                                                 |
| Overflow               | Overflow.Hidden                                                                                                                                                                                     |
| PaddingBottom          | 5                                                                                                                                                                                                   |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                                        |
| PaddingRight           | 5                                                                                                                                                                                                   |
| PaddingTop             | 5                                                                                                                                                                                                   |
| Size                   | 13                                                                                                                                                                                                  |
| Strikethrough          | false                                                                                                                                                                                               |
| Underline              | false                                                                                                                                                                                               |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                                                |
| Visible                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">And(Parent.Required, Parent.DisplayMode=DisplayMode.Edit)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>                                                     |
| Wrap                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                     |
| X                      | 0                                                                                                                                                                                                   |
| Y                      | DataCardKey4.Y                                                                                                                                                                                      |
| ZIndex                 | 4                                                                                                                                                                                                   |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>          |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(50, 49, 48, 1)</td></tr><tr><td style="background-color:#323130"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>          |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table></td></tr></table>          |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(161, 159, 157, 1)</td></tr><tr><td style="background-color:#A19F9D"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                     |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                     |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverBorderColor    | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverColor          | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                          |
| HoverFill           | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                           |
| PressedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| PressedColor        | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                          |
| PressedFill         | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                           |

### Child & Parent Controls

| Property       | Value                 |
| -------------- | --------------------- |
| Parent Control | User\_Type\_DataCard1 |

## StarVisible5\_1

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property | Value                                                                                                                                               |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| Live     | Live.Off                                                                                                                                            |
| Role     | TextRole.Default                                                                                                                                    |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"*"<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                                               |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Align.Center<td style="background-color:#ffcccc; width:50%;">Align.Left</td></tr></table>                                    |
| BorderStyle            | BorderStyle.Solid                                                                                                                                                                                   |
| BorderThickness        | 0                                                                                                                                                                                                   |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                                                    |
| FocusedBorderThickness | 0                                                                                                                                                                                                   |
| Font                   | Font.'Open Sans'                                                                                                                                                                                    |
| FontWeight             | FontWeight.Normal                                                                                                                                                                                   |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataCardKey5_1.Height<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                                   |
| Italic                 | false                                                                                                                                                                                               |
| LineHeight             | 1.2                                                                                                                                                                                                 |
| Overflow               | Overflow.Hidden                                                                                                                                                                                     |
| PaddingBottom          | 5                                                                                                                                                                                                   |
| PaddingLeft            | 5                                                                                                                                                                                                   |
| PaddingRight           | 5                                                                                                                                                                                                   |
| PaddingTop             | 5                                                                                                                                                                                                   |
| Size                   | 13                                                                                                                                                                                                  |
| Strikethrough          | false                                                                                                                                                                                               |
| Underline              | false                                                                                                                                                                                               |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                                                |
| Visible                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">And(Parent.Required, Parent.DisplayMode=DisplayMode.Edit)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>                                                     |
| Wrap                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                     |
| X                      | 0                                                                                                                                                                                                   |
| Y                      | DataCardKey5\_1.Y                                                                                                                                                                                   |
| ZIndex                 | 5                                                                                                                                                                                                   |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                      |
| ------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table> |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table> |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table>                                                                                                                                                                                                                                                                                         |
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

| Property       | Value                |
| -------------- | -------------------- |
| Parent Control | Imagem\_DataCard1\_1 |

## SubmitFormButton1

| Property                    | Value      |
| --------------------------- | ---------- |
| ![icon](resources/icon.png) | Type: icon |

### Behavior

| Property | Value                                                                                                                                                       |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">SubmitForm(Form1)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property               | Value                                                                                                                                                           |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                     |
| DisplayMode            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                     |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">50<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| Icon                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Icon.Check<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| PaddingBottom          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">12<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">12<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| PaddingRight           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">12<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| PaddingTop             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">12<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| TabIndex               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                     |
| Visible                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Or(editMode, newMode)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">50<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| X                      | 0                                                                                                                                                               |
| Y                      | 0                                                                                                                                                               |
| ZIndex                 | 18                                                                                                                                                              |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                      |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 120, 212, 1)</td></tr><tr><td style="background-color:#0078D4"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>   |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(245, 245, 245, 1)</td></tr><tr><td style="background-color:#F5F5F5"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(225, 223, 221, 1)</td></tr><tr><td style="background-color:#E1DFDD"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| Fill                | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                           |
| HoverBorderColor    | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| HoverColor          | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(16, 110, 190, 1)</td></tr><tr><td style="background-color:#106EBE"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>  |
| HoverFill           | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| PressedBorderColor  | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| PressedColor        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(16, 110, 190, 1)</td></tr><tr><td style="background-color:#106EBE"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>  |
| PressedFill         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |

### Child & Parent Controls

| Property       | Value                          |
| -------------- | ------------------------------ |
| Parent Control | SelectedRecordHeaderContainer1 |

## Subtitle1\_1

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Behavior

| Property | Value                                                                                                                                                    |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Select(Parent)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property | Value                                                                                                                                                             |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Live     | Live.Off                                                                                                                                                          |
| Role     | TextRole.Default                                                                                                                                                  |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.Username<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |
| Tooltip  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Username"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |

### Design

| Property      | Value                                                                                                                                                                                                                      |
| ------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align         | Align.Left                                                                                                                                                                                                                 |
| BorderStyle   | BorderStyle.Solid                                                                                                                                                                                                          |
| DisplayMode   | DisplayMode.Edit                                                                                                                                                                                                           |
| Font          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Font.'Segoe UI'<td style="background-color:#ffcccc; width:50%;">Font.'Open Sans'</td></tr></table>                                                  |
| FontWeight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(ThisItem.IsSelected, FontWeight.Semibold, FontWeight.Normal)<td style="background-color:#ffcccc; width:50%;">FontWeight.Normal</td></tr></table> |
| Height        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Self.Size * 1.8<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                                                                |
| Overflow      | Overflow.Hidden                                                                                                                                                                                                            |
| PaddingBottom | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                                                               |
| PaddingLeft   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">12<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                                                              |
| PaddingRight  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                                                               |
| PaddingTop    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                                                               |
| Size          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">12<td style="background-color:#ffcccc; width:50%;">13</td></tr></table>                                                                             |
| TabIndex      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">-1<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                               |
| VerticalAlign | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">VerticalAlign.Top<td style="background-color:#ffcccc; width:50%;">VerticalAlign.Middle</td></tr></table>                                            |
| Width         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Title1_1.Width<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>                                                                |
| X             | Title1\_1.X                                                                                                                                                                                                                |
| Y             | Title1\_1.Y + Title1\_1.Height                                                                                                                                                                                             |
| ZIndex        | 2                                                                                                                                                                                                                          |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>          |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(96, 94, 92, 1)</td></tr><tr><td style="background-color:#605E5C"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>          |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table>                                                                                                                                                                                                                                                                                                  |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(161, 159, 157, 1)</td></tr><tr><td style="background-color:#A19F9D"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                     |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                     |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverBorderColor    | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverColor          | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                          |
| HoverFill           | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                           |
| PressedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| PressedColor        | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                          |
| PressedFill         | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                           |

### Child & Parent Controls

| Property       | Value           |
| -------------- | --------------- |
| Parent Control | RecordsGallery1 |

## TableNameContainer1

| Property                                                                      | Value                               |
| ----------------------------------------------------------------------------- | ----------------------------------- |
| ![horizontalAutoLayoutContainer](resources/horizontalAutoLayoutContainer.png) | Type: horizontalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.Light<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">68<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Center<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Horizontal<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
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

| Property       | Value            |
| -------------- | ---------------- |
| Child Control  | TableNameLabel1  |
| Parent Control | ScreenContainer1 |

## TableNameLabel1

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property | Value                                                                                                                                                                                                     |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Live     | Live.Off                                                                                                                                                                                                  |
| Role     | TextRole.Default                                                                                                                                                                                          |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataSourceInfo([@Users_Info], DataSourceInfo.DisplayName)<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                          |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Align                  | Align.Left                                                                                                                                                                     |
| BorderStyle            | BorderStyle.Solid                                                                                                                                                              |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                               |
| FocusedBorderThickness | 0                                                                                                                                                                              |
| Font                   | Font.'Open Sans'                                                                                                                                                               |
| FontWeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">FontWeight.Semibold<td style="background-color:#ffcccc; width:50%;">FontWeight.Normal</td></tr></table> |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">68<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                                 |
| Overflow               | Overflow.Hidden                                                                                                                                                                |
| PaddingBottom          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                  |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                  |
| PaddingRight           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                  |
| PaddingTop             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                  |
| Size                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;">13</td></tr></table>                                 |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                           |
| Width                  | 150                                                                                                                                                                            |
| Wrap                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| X                      | 0                                                                                                                                                                              |
| Y                      | 0                                                                                                                                                                              |
| ZIndex                 | 3                                                                                                                                                                              |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>          |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(20, 52, 84, 1)</td></tr><tr><td style="background-color:#143454"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>          |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table>                                                                                                                                                                                                                                                                                                  |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(186, 186, 186, 1)</td></tr><tr><td style="background-color:#BABABA"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                     |
| Fill                | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(245, 208, 0, 1)</td></tr><tr><td style="background-color:#F5D000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>         |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverBorderColor    | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverColor          | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                          |
| HoverFill           | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                           |
| PressedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| PressedColor        | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                          |
| PressedFill         | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                           |

### Child & Parent Controls

| Property       | Value               |
| -------------- | ------------------- |
| Parent Control | TableNameContainer1 |

## Title1\_1

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Behavior

| Property | Value                                                                                                                                                    |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Select(Parent)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property | Value                                                                                                                                                         |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Live     | Live.Off                                                                                                                                                      |
| Role     | TextRole.Default                                                                                                                                              |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.Name<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |
| Tooltip  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Name"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |

### Design

| Property      | Value                                                                                                                                                                                                                      |
| ------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align         | Align.Left                                                                                                                                                                                                                 |
| BorderStyle   | BorderStyle.Solid                                                                                                                                                                                                          |
| DisplayMode   | DisplayMode.Edit                                                                                                                                                                                                           |
| Font          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Font.'Segoe UI'<td style="background-color:#ffcccc; width:50%;">Font.'Open Sans'</td></tr></table>                                                  |
| FontWeight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(ThisItem.IsSelected, FontWeight.Semibold, FontWeight.Normal)<td style="background-color:#ffcccc; width:50%;">FontWeight.Normal</td></tr></table> |
| Height        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Self.Size * 1.8<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                                                                |
| Overflow      | Overflow.Hidden                                                                                                                                                                                                            |
| PaddingBottom | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                                                               |
| PaddingLeft   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">12<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                                                              |
| PaddingRight  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                                                               |
| PaddingTop    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                                                               |
| Size          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">14<td style="background-color:#ffcccc; width:50%;">13</td></tr></table>                                                                             |
| TabIndex      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">-1<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                               |
| VerticalAlign | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">VerticalAlign.Top<td style="background-color:#ffcccc; width:50%;">VerticalAlign.Middle</td></tr></table>                                            |
| Width         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.TemplateWidth - 86<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>                                                     |
| X             | 16                                                                                                                                                                                                                         |
| Y             | (Parent.TemplateHeight \- (Self.Size\*1.8 + Subtitle1\_1.Size\*1.8 + 2 + Body1.Size\*1.8)) \/ 2                                                                                                                            |
| ZIndex        | 1                                                                                                                                                                                                                          |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>          |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(50, 49, 48, 1)</td></tr><tr><td style="background-color:#323130"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>          |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table>                                                                                                                                                                                                                                                                                                  |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(161, 159, 157, 1)</td></tr><tr><td style="background-color:#A19F9D"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                     |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                     |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverBorderColor    | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverColor          | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                          |
| HoverFill           | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                           |
| PressedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| PressedColor        | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                          |
| PressedFill         | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                           |

### Child & Parent Controls

| Property       | Value           |
| -------------- | --------------- |
| Parent Control | RecordsGallery1 |

## User\_Type\_DataCard1

| Property                                      | Value               |
| --------------------------------------------- | ------------------- |
| ![typedDataCard](resources/typedDataCard.png) | Type: typedDataCard |

### Data

| Property    | Value                                                                                                                                                                                                                |
| ----------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DataField   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"crfe1_user_type"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                          |
| Default     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.User_Type<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                         |
| DisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataSourceInfo([@Users_Info],DataSourceInfo.DisplayName,"crfe1_user_type")<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Required    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                       |
| Update      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataCardValue4.Selected.Value<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                              |

### Design

| Property    | Value                                                                                                                                                        |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderStyle | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayMode<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">50<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">458<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| X           | 0                                                                                                                                                            |
| Y           | 2                                                                                                                                                            |
| ZIndex      | 24                                                                                                                                                           |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                      |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(245, 245, 245, 1)</td></tr><tr><td style="background-color:#F5F5F5"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Child Control  | StarVisible4   |
| Child Control  | DataCardKey4   |
| Child Control  | DataCardValue4 |
| Child Control  | ErrorMessage4  |
| Parent Control | Form1          |

## Username\_DataCard1

| Property                                      | Value               |
| --------------------------------------------- | ------------------- |
| ![typedDataCard](resources/typedDataCard.png) | Type: typedDataCard |

### Data

| Property    | Value                                                                                                                                                                                                               |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DataField   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"crfe1_password"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                          |
| Default     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.Username<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                         |
| DisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataSourceInfo([@Users_Info],DataSourceInfo.DisplayName,"crfe1_password")<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| MaxLength   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataSourceInfo([@Users_Info], DataSourceInfo.MaxLength, "crfe1_password")<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Required    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                      |
| Update      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataCardValue2.Text<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                       |

### Design

| Property    | Value                                                                                                                                                        |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderStyle | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayMode<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">50<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">458<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| X           | 0                                                                                                                                                            |
| Y           | 0                                                                                                                                                            |
| ZIndex      | 24                                                                                                                                                           |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                      |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(245, 245, 245, 1)</td></tr><tr><td style="background-color:#F5F5F5"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Child Control  | StarVisible2   |
| Child Control  | DataCardKey2   |
| Child Control  | DataCardValue2 |
| Child Control  | ErrorMessage2  |
| Parent Control | Form1          |
