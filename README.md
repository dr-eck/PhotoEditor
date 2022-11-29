# PhotoEditor
Microsoft's PhotoEditor sample migrated to WinUI 3

There are currently 2 MIDL2011 errors preventing compilation:

Error	MIDL2011	[msg]unresolved type declaration [context]: Microsoft.UI.Xaml.Data.INotifyPropertyChanged [ RuntimeClass 'PhotoEditor.Photo'  ]	PhotoEditor	C:\Users\dreck\Source\Repos\Windows-appsample-photo-editor\PhotoEditor\Photo.idl	28	

Error	MIDL2011	[msg]unresolved type declaration [context]: Microsoft.UI.Xaml.Controls.Page [ RuntimeClass 'PhotoEditor.DetailPage'  ]	PhotoEditor	C:\Users\dreck\Source\Repos\Windows-appsample-photo-editor\PhotoEditor\DetailPage.idl	30	

I don't know enough about MIDL to know how to fix these errors.  What's really strange is that Photo.idl compiled earlier in the process.  This probably means that the error is somewhere else, but I have no idea where to look.
