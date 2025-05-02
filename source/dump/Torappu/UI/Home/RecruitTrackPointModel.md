# RecruitTrackPointModel

**Namespace:** `Torappu.UI.Home`


## Fields

- `Int32 m_finishedSlotNum`


## Properties

- `Boolean isShow`

- `Int32 finishedSlotNum`


## Methods

- `Boolean get_isShow()`

- `Int32 get_finishedSlotNum()`

- `Void UpdateState(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class RecruitTrackPointModel : ITrackPointModel, IHotfixable
{
	private Int32 m_finishedSlotNum; // 0x10
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_get_finishedSlotNum; // 0x8
	private static DelegateBridge __Hotfix0_UpdateState; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean isShow { get; }
	public Int32 finishedSlotNum { get; }

	// RVA: 0x281afb8 VA: 0x7594e32fb8
	public Boolean get_isShow() { }
	// RVA: 0x281b028 VA: 0x7594e33028
	public Int32 get_finishedSlotNum() { }
	// RVA: 0x281b090 VA: 0x7594e33090
	public Void UpdateState(Object param) { }
	// RVA: 0x281b1dc VA: 0x7594e331dc
	public Void .ctor() { }
}
```