# PullToRefreshListView for WindowsPhone

This is a bit changet version of control from here: https://github.com/XamlBrewer/PullToRefreshListView
This project is cut to be only Windows Phone version and is published to Nuget.


```xaml
<controls:PullToRefreshListView ItemsSource="{Binding Items}"
                                RefreshCommand="{Binding RefreshCommand}"
                                ArrowColor="{StaticResource MagooShirtGreen}"
                                Background="LightBlue" />
```

By default arrow color is set to PhoneAccentBrush and text color is set to is PhoneForegroundBrush;

Grab it from nuget: https://www.nuget.org/packages/PullToRefreshListView/
