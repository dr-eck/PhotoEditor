# PhotoEditor
Microsoft's PhotoEditor sample migrated to WinUI 3

The instructions are here:  https://learn.microsoft.com/en-us/windows/apps/windows-app-sdk/migrate-to-windows-app-sdk/case-study-2

One thing missing from Microsoft's instructions is that it is necessary to change all instances of "from_abi" to "get_self" in MainPage.xaml.cpp and DetailPage.xaml.cpp

Thanks to Tim-Weis for explaining this.
