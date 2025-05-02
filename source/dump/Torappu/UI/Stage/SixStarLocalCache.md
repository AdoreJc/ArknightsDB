# SixStarLocalCache

**Namespace:** `Torappu.UI.Stage`


## Methods

- `Boolean GetIsPreviewSelectSixStar(String)`

- `Void SaveIsSelectSixStar(String, Boolean)`

- `SixStarLocalMemData _EnsureMemCacheData()`

- `Void _SaveData(SixStarLocalMemData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class SixStarLocalCache : Singleton`1
{
	private Data`1 m_memData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GetIsPreviewSelectSixStar; // 0x8
	private static DelegateBridge __Hotfix0_SaveIsSelectSixStar; // 0x10
	private static DelegateBridge __Hotfix0__EnsureMemCacheData; // 0x18
	private static DelegateBridge __Hotfix0__SaveData; // 0x20


	// RVA: 0x2f51354 VA: 0x7595569354
	private Void .ctor() { }
	// RVA: 0x2f513e4 VA: 0x75955693e4
	public Boolean GetIsPreviewSelectSixStar(String zoneId) { }
	// RVA: 0x2f5161c VA: 0x759556961c
	public Void SaveIsSelectSixStar(String zoneId, Boolean isPreviewSelectedSixStar) { }
	// RVA: 0x2f514b8 VA: 0x75955694b8
	private SixStarLocalMemData _EnsureMemCacheData() { }
	// RVA: 0x2f5177c VA: 0x759556977c
	private Void _SaveData(SixStarLocalMemData data) { }
}
```