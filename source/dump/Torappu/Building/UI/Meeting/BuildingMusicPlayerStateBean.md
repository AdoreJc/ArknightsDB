# BuildingMusicPlayerStateBean

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `MusicPlayerProperty musicPlayerProp`


## Methods

- `Void InitData()`

- `Void RefreshData()`

- `Void InitDefaultModeData()`

- `Void InitVisitModeData()`

- `Void RefreshDefaultModeData()`

- `Void ChangeSortOrder()`

- `Void SetPlayingMusic(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class BuildingMusicPlayerStateBean : IStateBean, IHotfixable
{
	public MusicPlayerProperty musicPlayerProp; // 0x10
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshData; // 0x8
	private static DelegateBridge __Hotfix0_InitDefaultModeData; // 0x10
	private static DelegateBridge __Hotfix0_InitVisitModeData; // 0x18
	private static DelegateBridge __Hotfix0_RefreshDefaultModeData; // 0x20
	private static DelegateBridge __Hotfix0_ChangeSortOrder; // 0x28
	private static DelegateBridge __Hotfix0_SetPlayingMusic; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x3dea48c VA: 0x759640248c
	public Void InitData() { }
	// RVA: 0x3dea954 VA: 0x7596402954
	public Void RefreshData() { }
	// RVA: 0x3deb59c VA: 0x759640359c
	public Void InitDefaultModeData() { }
	// RVA: 0x3deb4d8 VA: 0x75964034d8
	public Void InitVisitModeData() { }
	// RVA: 0x3deb668 VA: 0x7596403668
	public Void RefreshDefaultModeData() { }
	// RVA: 0x3deaa94 VA: 0x7596402a94
	public Void ChangeSortOrder() { }
	// RVA: 0x3deae4c VA: 0x7596402e4c
	public Void SetPlayingMusic(String bgmId) { }
	// RVA: 0x3deb004 VA: 0x7596403004
	public Void .ctor() { }
}
```