# AssetPackManagerDownloadStatusCallback

**Namespace:** ` `


## Methods

- `Void onStatusUpdate(String, Int32, Int64, Int64, Int32, Int32)`


## Dump
```C#
// Dll : UnityEngine.AndroidJNIModule.dll
// Namespace : 
private class AssetPackManagerDownloadStatusCallback : AndroidJavaProxy
{
	private Action`1 m_Callback; // 0x20
	private String[] m_AssetPacks; // 0x28


	// RVA: 0x68440cc VA: 0x7598e5c0cc
	public Void .ctor(Action`1 callback, String[] assetPacks) { }
	// RVA: 0x6844168 VA: 0x7598e5c168
	private Void onStatusUpdate(String assetPackName, Int32 assetPackStatus, Int64 assetPackSize, Int64 assetPackBytesDownloaded, Int32 assetPackTransferProgress, Int32 assetPackErrorCode) { }
}
```