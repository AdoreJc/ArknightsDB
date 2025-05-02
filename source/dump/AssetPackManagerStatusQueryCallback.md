# AssetPackManagerStatusQueryCallback

**Namespace:** ` `


## Fields

- `Int64 m_Size`


## Methods

- `Void onStatusResult(Int64, String[], Int32[], Int32[])`


## Dump
```C#
// Dll : UnityEngine.AndroidJNIModule.dll
// Namespace : 
private class AssetPackManagerStatusQueryCallback : AndroidJavaProxy
{
	private Action`2 m_Callback; // 0x20
	private List`1 m_AssetPackNames; // 0x28
	private List`1 m_States; // 0x30
	private Int64 m_Size; // 0x38


	// RVA: 0x68443a0 VA: 0x7598e5c3a0
	public Void .ctor(Action`2 callback, String[] assetPacks) { }
	// RVA: 0x68444c0 VA: 0x7598e5c4c0
	private Void onStatusResult(Int64 totalBytes, String[] assetPackNames, Int32[] assetPackStatuses, Int32[] assetPackErrorCodes) { }
}
```