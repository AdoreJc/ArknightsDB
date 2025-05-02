# OpenServerV2MainViewModel

**Namespace:** `Torappu.UI.Home.Activity`


## Fields

- `OpenServerV2ChainLoginViewModel m_chainLoginViewModel`

- `OpenServerV2MissionViewModel m_missionViewModel`

- `OpenServerV2TotalCheckinViewModel m_totalCheckinViewModel`


## Properties

- `OpenServerV2ChainLoginViewModel chainLoginViewModel`

- `OpenServerV2MissionViewModel missionViewModel`

- `OpenServerV2TotalCheckinViewModel totalCheckinViewModel`


## Methods

- `OpenServerV2ChainLoginViewModel get_chainLoginViewModel()`

- `OpenServerV2MissionViewModel get_missionViewModel()`

- `OpenServerV2TotalCheckinViewModel get_totalCheckinViewModel()`

- `Void LoadData()`

- `Void UpdateData()`

- `Boolean CheckIfFuncTypeAvailable(OpenServerFuncType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home.Activity
public class OpenServerV2MainViewModel : IHotfixable
{
	private OpenServerV2ChainLoginViewModel m_chainLoginViewModel; // 0x10
	private OpenServerV2MissionViewModel m_missionViewModel; // 0x18
	private OpenServerV2TotalCheckinViewModel m_totalCheckinViewModel; // 0x20
	private static DelegateBridge __Hotfix0_get_chainLoginViewModel; // 0x0
	private static DelegateBridge __Hotfix0_get_missionViewModel; // 0x8
	private static DelegateBridge __Hotfix0_get_totalCheckinViewModel; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0_UpdateData; // 0x20
	private static DelegateBridge __Hotfix0_CheckIfFuncTypeAvailable; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public OpenServerV2ChainLoginViewModel chainLoginViewModel { get; }
	public OpenServerV2MissionViewModel missionViewModel { get; }
	public OpenServerV2TotalCheckinViewModel totalCheckinViewModel { get; }

	// RVA: 0x2853990 VA: 0x7594e6b990
	public OpenServerV2ChainLoginViewModel get_chainLoginViewModel() { }
	// RVA: 0x28569fc VA: 0x7594e6e9fc
	public OpenServerV2MissionViewModel get_missionViewModel() { }
	// RVA: 0x28570a4 VA: 0x7594e6f0a4
	public OpenServerV2TotalCheckinViewModel get_totalCheckinViewModel() { }
	// RVA: 0x2855404 VA: 0x7594e6d404
	public Void LoadData() { }
	// RVA: 0x2855a54 VA: 0x7594e6da54
	public Void UpdateData() { }
	// RVA: 0x2855c9c VA: 0x7594e6dc9c
	public Boolean CheckIfFuncTypeAvailable(OpenServerFuncType funcType) { }
	// RVA: 0x2855f90 VA: 0x7594e6df90
	public Void .ctor() { }
}
```