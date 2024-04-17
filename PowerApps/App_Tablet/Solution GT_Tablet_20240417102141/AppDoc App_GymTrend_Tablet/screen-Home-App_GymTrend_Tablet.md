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

## Home

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

| Property      | Value     |
| ------------- | --------- |
| Child Control | cnt\_main |

## cnt\_body

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
| Child Control  | Container6    |
| Child Control  | Container6\_1 |
| Parent Control | cnt\_main     |

## cnt\_footer

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
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">cnt_header.Height/2<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
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

| Property       | Value     |
| -------------- | --------- |
| Child Control  | Footer\_1 |
| Parent Control | cnt\_main |

## cnt\_header

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

| Property       | Value     |
| -------------- | --------- |
| Child Control  | Header\_1 |
| Parent Control | cnt\_main |

## cnt\_main

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

| Property       | Value       |
| -------------- | ----------- |
| Child Control  | cnt\_header |
| Child Control  | cnt\_body   |
| Child Control  | cnt\_footer |
| Parent Control | Home        |

## Component1\_1

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
| Visible  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| Width    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Component1_1.Menu_Width<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| X        | 0                                                                                                                                                                 |
| Y        | 0                                                                                                                                                                 |
| ZIndex   | 1                                                                                                                                                                 |

### Color Properties

| Property | Value                                                                                                                                                                                                                                                                                                                                        |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Fill     | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(146, 146, 146, 0.2)</td></tr><tr><td style="background-color:#929292"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | Container6 |

## Container6

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
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Component1_1.Menu_Width<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| X                    | 0                                                                                                                                                                    |
| Y                    | 0                                                                                                                                                                    |
| ZIndex               | 1                                                                                                                                                                    |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value         |
| -------------- | ------------- |
| Child Control  | Component1\_1 |
| Parent Control | cnt\_body     |

## Container6\_1

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

| Property       | Value      |
| -------------- | ---------- |
| Child Control  | Container7 |
| Parent Control | cnt\_body  |

## Container7

| Property                                                      | Value                       |
| ------------------------------------------------------------- | --------------------------- |
| ![manualLayoutContainer](resources/manualLayoutContainer.png) | Type: manualLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.Light<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">200<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
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
| ZIndex               | 1                                                                                                                                                                    |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value         |
| -------------- | ------------- |
| Child Control  | Image6        |
| Child Control  | Label1        |
| Child Control  | Label1\_2     |
| Parent Control | Container6\_1 |

## Footer\_1

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

| Property       | Value       |
| -------------- | ----------- |
| Parent Control | cnt\_footer |

## Header\_1

| Property                              | Value           |
| ------------------------------------- | --------------- |
| ![component](resources/component.png) | Type: component |

### Design

| Property | Value                                                                                                                                          |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| Height   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">80<td style="background-color:#ffcccc; width:50%;"></td></tr></table>   |
| Width    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1366<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| X        | 0                                                                                                                                              |
| Y        | 0                                                                                                                                              |
| ZIndex   | 1                                                                                                                                              |

### Color Properties

| Property | Value                                                                                                                                                                                                                                                                                                                                |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Fill     | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value       |
| -------------- | ----------- |
| Parent Control | cnt\_header |

## Image6

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![image](resources/image.png) | Type: image |

### Data

| Property | Value                                                                                                                                                                                                                                    |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Image    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'Default_create_a_simple_profile_picture_for_a_gym_app_has_to_b_2-removebg-preview'<td style="background-color:#ffcccc; width:50%;">SampleImage</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                         |
| ---------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle            | BorderStyle.Solid                                                                                                                                                             |
| BorderThickness        | 0                                                                                                                                                                             |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                              |
| FocusedBorderThickness | 2                                                                                                                                                                             |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">370<td style="background-color:#ffcccc; width:50%;">100</td></tr></table>                              |
| ImagePosition          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ImagePosition.Fill<td style="background-color:#ffcccc; width:50%;">ImagePosition.Fit</td></tr></table> |
| ImageRotation          | ImageRotation.None                                                                                                                                                            |
| PaddingBottom          | 0                                                                                                                                                                             |
| PaddingLeft            | 0                                                                                                                                                                             |
| PaddingRight           | 0                                                                                                                                                                             |
| PaddingTop             | 0                                                                                                                                                                             |
| RadiusBottomLeft       | 0                                                                                                                                                                             |
| RadiusBottomRight      | 0                                                                                                                                                                             |
| RadiusTopLeft          | 0                                                                                                                                                                             |
| RadiusTopRight         | 0                                                                                                                                                                             |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">382<td style="background-color:#ffcccc; width:50%;">100</td></tr></table>                              |
| X                      | Parent.Width\/2\-Image6.Width\/2                                                                                                                                              |
| Y                      | (Parent.Height\/2\-Image6.Height\/2)\-80                                                                                                                                      |
| ZIndex                 | 1                                                                                                                                                                             |

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

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | Container7 |

## Label1

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property | Value                                                                                                                                                                                                           |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Live     | Live.Off                                                                                                                                                                                                        |
| Role     | TextRole.Default                                                                                                                                                                                                |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Bem-vindo, " & LookUp(Users_Info,Username = User().Email,Name)<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                      |
| ---------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Align.Center<td style="background-color:#ffcccc; width:50%;">Align.Left</td></tr></table>           |
| BorderStyle            | BorderStyle.Solid                                                                                                                                                          |
| BorderThickness        | 0                                                                                                                                                                          |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                           |
| FocusedBorderThickness | 0                                                                                                                                                                          |
| Font                   | Font.'Open Sans'                                                                                                                                                           |
| FontWeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">FontWeight.Bold<td style="background-color:#ffcccc; width:50%;">FontWeight.Normal</td></tr></table> |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">50<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                             |
| Italic                 | false                                                                                                                                                                      |
| LineHeight             | 1.2                                                                                                                                                                        |
| Overflow               | Overflow.Hidden                                                                                                                                                            |
| PaddingBottom          | 5                                                                                                                                                                          |
| PaddingLeft            | 5                                                                                                                                                                          |
| PaddingRight           | 5                                                                                                                                                                          |
| PaddingTop             | 5                                                                                                                                                                          |
| Size                   | 13                                                                                                                                                                         |
| Strikethrough          | false                                                                                                                                                                      |
| Underline              | false                                                                                                                                                                      |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                       |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Image6.Width<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>                  |
| X                      | Image6.X                                                                                                                                                                   |
| Y                      | Image6.Height+Image6.Y+10                                                                                                                                                  |
| ZIndex                 | 2                                                                                                                                                                          |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table>    |
| Color               | <table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table>    |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| FocusedBorderColor  | Self.BorderColor                                                                                                      |
| HoverBorderColor    | Self.BorderColor                                                                                                      |
| HoverColor          | Self.Color                                                                                                            |
| HoverFill           | Self.Fill                                                                                                             |
| PressedBorderColor  | Self.BorderColor                                                                                                      |
| PressedColor        | Self.Color                                                                                                            |
| PressedFill         | Self.Fill                                                                                                             |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | Container7 |

## Label1\_2

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property | Value                                                                                                                                                         |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Live     | Live.Off                                                                                                                                                      |
| Role     | TextRole.Default                                                                                                                                              |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Text(Today())<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                            |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Align.Center<td style="background-color:#ffcccc; width:50%;">Align.Left</td></tr></table> |
| BorderStyle            | BorderStyle.Solid                                                                                                                                                |
| BorderThickness        | 0                                                                                                                                                                |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                 |
| FocusedBorderThickness | 0                                                                                                                                                                |
| Font                   | Font.'Open Sans'                                                                                                                                                 |
| FontWeight             | FontWeight.Normal                                                                                                                                                |
| Height                 | 40                                                                                                                                                               |
| Italic                 | false                                                                                                                                                            |
| LineHeight             | 1.2                                                                                                                                                              |
| Overflow               | Overflow.Hidden                                                                                                                                                  |
| PaddingBottom          | 5                                                                                                                                                                |
| PaddingLeft            | 5                                                                                                                                                                |
| PaddingRight           | 5                                                                                                                                                                |
| PaddingTop             | 5                                                                                                                                                                |
| Size                   | 13                                                                                                                                                               |
| Strikethrough          | false                                                                                                                                                            |
| Underline              | false                                                                                                                                                            |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                             |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Image6.Width<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>        |
| X                      | Image6.X                                                                                                                                                         |
| Y                      | Image6.Height+Image6.Y+Label1.Height+20                                                                                                                          |
| ZIndex                 | 4                                                                                                                                                                |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table>    |
| Color               | <table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table>    |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| FocusedBorderColor  | Self.BorderColor                                                                                                      |
| HoverBorderColor    | Self.BorderColor                                                                                                      |
| HoverColor          | Self.Color                                                                                                            |
| HoverFill           | Self.Fill                                                                                                             |
| PressedBorderColor  | Self.BorderColor                                                                                                      |
| PressedColor        | Self.Color                                                                                                            |
| PressedFill         | Self.Fill                                                                                                             |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | Container7 |
