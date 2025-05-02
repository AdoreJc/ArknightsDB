# ArchiveEndbookController

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveEndbookListDataBinder _dataBinder`

- `ArchiveEndbookDetailDataBinder _detailBinder`


## Methods

- `Void OnEndItemClick(Int32)`

- `Void OnIndexConfirm(Int32)`

- `Void <>xLuaBaseProxy_Init(ActArchiveProxy)`

- `Void <>xLuaBaseProxy_OnItemClick(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveEndbookController : ActArchiveController
{
	private ArchiveEndbookListDataBinder _dataBinder; // 0x38
	private ArchiveEndbookDetailDataBinder _detailBinder; // 0x40
	public Action`2 onItemClicked; // 0x48
	public Action`2 onIndexConfirm; // 0x50
	public Action`2 onEndItemClicked; // 0x58
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_InitAndAchieveDataBinders; // 0x8
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x10
	private static DelegateBridge __Hotfix0_OnEndItemClick; // 0x18
	private static DelegateBridge __Hotfix0_OnIndexConfirm; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x304c29c VA: 0x759566429c
	public override Void Init(ActArchiveProxy proxy) { }
	// RVA: 0x304c320 VA: 0x7595664320
	public List`1 InitAndAchieveDataBinders() { }
	// RVA: 0x304c5d0 VA: 0x75956645d0
	public override Void OnItemClick(String funcId) { }
	// RVA: 0x304c674 VA: 0x7595664674
	public Void OnEndItemClick(Int32 index) { }
	// RVA: 0x304c718 VA: 0x7595664718
	public Void OnIndexConfirm(Int32 index) { }
	// RVA: 0x304c7bc VA: 0x75956647bc
	public Void .ctor() { }
	// RVA: 0x304c82c VA: 0x759566482c
	private Void <>xLuaBaseProxy_Init(ActArchiveProxy P0) { }
	// RVA: 0x304c834 VA: 0x7595664834
	private Void <>xLuaBaseProxy_OnItemClick(String P0) { }
}
```