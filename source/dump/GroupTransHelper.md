# GroupTransHelper

**Namespace:** ` `


## Fields

- `Single delayToHideMat`

- `Boolean showHp`

- `Boolean isInDisplayState`

- `UIBattleSandboxConstruct m_construct`

- `Single m_isTransingTime`

- `Boolean m_isMatShown`

- `Tween m_matBgTween`


## Methods

- `Void Init(UIBattleSandboxConstruct)`

- `Void _HideMat()`

- `Void _ShowMat()`

- `Void Update(Single)`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class GroupTransHelper : IHotfixable
{
	public Single delayToHideMat; // 0x10
	public Boolean showHp; // 0x14
	public Boolean isInDisplayState; // 0x15
	private UIBattleSandboxConstruct m_construct; // 0x18
	private Single m_isTransingTime; // 0x20
	private Boolean m_isMatShown; // 0x24
	private Tween m_matBgTween; // 0x28
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0__HideMat; // 0x8
	private static DelegateBridge __Hotfix0__ShowMat; // 0x10
	private static DelegateBridge __Hotfix0_Update; // 0x18
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x209513c VA: 0x75946ad13c
	public Void Init(UIBattleSandboxConstruct construct) { }
	// RVA: 0x2097ca0 VA: 0x75946afca0
	private Void _HideMat() { }
	// RVA: 0x2097e1c VA: 0x75946afe1c
	private Void _ShowMat() { }
	// RVA: 0x20953cc VA: 0x75946ad3cc
	public Void Update(Single deltaTime) { }
	// RVA: 0x20958d8 VA: 0x75946ad8d8
	public Void OnDestroy() { }
	// RVA: 0x2097830 VA: 0x75946af830
	public Void .ctor() { }
}
```