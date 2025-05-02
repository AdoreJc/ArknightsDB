# MixStoryLocalCache

**Namespace:** `Torappu.UI.Stage.MixStory`


## Methods

- `String GetLastVisitedStorySet()`

- `Void SaveLastVisitedStorySet(String)`

- `OverallDisplayFeature GetOverallDisplayFeature()`

- `Void SaveOverallDisplayFeature(OverallDisplayFeature)`

- `Data _EnsureMemCacheData()`

- `Void _SaveData(Data)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.MixStory
public class MixStoryLocalCache : Singleton`1
{
	private Data`1 m_memData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GetLastVisitedStorySet; // 0x8
	private static DelegateBridge __Hotfix0_SaveLastVisitedStorySet; // 0x10
	private static DelegateBridge __Hotfix0_GetOverallDisplayFeature; // 0x18
	private static DelegateBridge __Hotfix0_SaveOverallDisplayFeature; // 0x20
	private static DelegateBridge __Hotfix0__EnsureMemCacheData; // 0x28
	private static DelegateBridge __Hotfix0__SaveData; // 0x30


	// RVA: 0x2fe37b0 VA: 0x75955fb7b0
	private Void .ctor() { }
	// RVA: 0x2fe3840 VA: 0x75955fb840
	public String GetLastVisitedStorySet() { }
	// RVA: 0x2fe39d8 VA: 0x75955fb9d8
	public Void SaveLastVisitedStorySet(String lastVisitedStorySet) { }
	// RVA: 0x2fe3b30 VA: 0x75955fbb30
	public OverallDisplayFeature GetOverallDisplayFeature() { }
	// RVA: 0x2fe3bcc VA: 0x75955fbbcc
	public Void SaveOverallDisplayFeature(OverallDisplayFeature overallDisplayFeature) { }
	// RVA: 0x2fe38d8 VA: 0x75955fb8d8
	private Data _EnsureMemCacheData() { }
	// RVA: 0x2fe3a84 VA: 0x75955fba84
	private Void _SaveData(Data data) { }
}
```