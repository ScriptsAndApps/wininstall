
Dism /Get-ImageInfo /ImageFile:I:\sources\install.esd


Dism /Export-Image /SourceImageFile:I:\sources\install.esd /SourceIndex:6 /DestinationImageFile:D:\sources\install.wim /Compress:max /CheckIntegrity
