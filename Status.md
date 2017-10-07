# Status

## To-Do
* Accessibility
* TimePicker
* List (Lot of work)
* Serializer
* NativeViewWrapper
* NavigationMenu

## Pages

### ContentPage

A [ContentPage](https://developer.xamarin.com/api/type/Xamarin.Forms.ContentPage/) is a Page displaying a single View, often a container like a StackLayout or ScrollView.

Property | Status
------ | ------
BackgroundColor   | Done  
Appearing   | Done  
Disappearing   | Done  

### MasterDetailPage

A [Page](https://developer.xamarin.com/api/type/Xamarin.Forms.MasterDetailPage/) that manages two panes of information: A master page that presents data at a high level, and a detail page that displays low-level details about information in the master.

Property | Status
------ | ------
Detail   | Done  
IsGestureEnabled   | Pending  
IsPresented   | Done  
Master   | Done  
MasterBehavior   | Pending  
ShouldShowToolBarButton   | Pending  
IsPresentedChanged   | Done  

### NavigationPage

A [Page](https://developer.xamarin.com/api/type/Xamarin.Forms.NavigationPage/) that manages the navigation and user-experience of a stack of other pages.

Property | Status
------ | ------
Animate   | Done  
Add   | Done  
Remove   | Done  

### TabbedPage

[Displays](https://developer.xamarin.com/api/type/Xamarin.Forms.TabbedPage/) an array of tabs across the top of the screen, each of which loads content onto the screen.

Property | Status
------ | ------
BarBackgroundColor   | Done  
BarTextColor   | Done  
ItemsSource   | Done  
ItemTemplate   | Done  
SelectedItem   | Done  
GetIndex   | Done  
GetPageByIndex   | Done  
SetIndex   | Done  
Appearing   | Done  
Disappearing   | Done  
CurrentPageChanged   | Done  
PagesChanged   | Done 

### CarouselPage

The Xamarin.Forms [CarouselPage](https://developer.xamarin.com/guides/xamarin-forms/application-fundamentals/navigation/carousel-page/) is a page that users can swipe from side to side to navigate through pages of content, like a gallery. 

Property | Status
------ | ------
ItemsSource   | Done  
ItemTemplate   | Done  
CurrentPage   | Done  
Children   | Done  
BackgroundImage   | Done  
Icon   | Pending  
IsBusy   | Done  
Padding   | Done  
Tittle   | Done  
ToolbarItems   | Done  
CurrentPageChanged   | Done  
PagesChanged   | Done  
LayoutChanged   | Done  
Appearing   | Done  
Disappearing   | Done  

## Views

### ActivityIndicator

The [ActivityIndicator](https://developer.xamarin.com/api/type/Xamarin.Forms.ActivityIndicator/) control gives a visual clue to the user that something is happening, without information about its progress.

Property | Status
------ | ------
BackgroundColor   | Pending  
IsRunning   | Done  
Color   | Done  

### ActionSheets

The UIActionSheet is a common UI element in iOS. The Xamarin.Forms [DisplayActionSheet](https://developer.xamarin.com/guides/xamarin-forms/application-fundamentals/navigation/pop-ups/) method lets you include this control in cross-platforms apps, rendering native alternatives.

Property | Status
------ | ------
Title   | Done  
Cancel   | Done  
Extras   | Done  
Destruction   | Done  

### BoxView

[BoxView](https://developer.xamarin.com/api/type/Xamarin.Forms.BoxView/) is a useful stand-in for images or custom elements when doing initial prototyping. 

Property | Status
------ | ------
BackgroundColor   | Done  
Color   | Done  

### Button

A [button](https://developer.xamarin.com/api/type/Xamarin.Forms.Button/) View that reacts to touch events.

Property | Status
------ | ------
BackgroundColor   | Done  
IsEnabled   | Done  
Command   | Done  
CommandParameter   | Done  
ContentLayout   | Done  
Text   | Done  
TextColor   | Done  
Font   | Done  
FontFamily   | Done  
FontAttributes   | Done  
BorderWidth   | Done  
BorderColor   | Done  
BorderRadius   | Pending  
Image   | Done  
Clicked   | Done  
Pressed   | Done  
Released   | Done  

### DatePicker

The visual representation of a [DatePicker](https://developer.xamarin.com/api/type/Xamarin.Forms.DatePicker/) is very similar to the one of Entry, except that a special control for picking a date appears in place of a keyboard.

Property | Status
------ | ------
BackgroundColor   | Done  
Format   | Pending 
Date   | Done  
MinimumDate   | Done  
MaximumDate   | Done  
TextColor   | Done  
DateSelected   | Done  

### Editor

The [Editor](https://developer.xamarin.com/guides/xamarin-forms/user-interface/text/editor/) control is used to accept multi-line input.

Property | Status
------ | ------
BackgroundColor   | Done  
IsEnabled   | Done  
Text   | Done  
FontFamily   | Done  
FontSize   | Done  
FontAttributes   | Done  
TextColor   | Done  
TextChanged   | Done  
