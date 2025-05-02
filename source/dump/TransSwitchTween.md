# TransSwitchTween

**Namespace:** ` `


## Fields

- `SandboxV2NodeFloatView m_closure`


## Methods

- `Void SetBuffer(Int32, Buffer)`

- `Void <GenerateTweenOfHide>b__4_1(Single)`

- `Void <GenerateTweenOfShow>b__5_1(Single)`

- `Void <>xLuaBaseProxy_AfterHideEffect()`

- `Void <>xLuaBaseProxy_AfterShowEffect()`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class TransSwitchTween : UISwitchTween
{
	private SandboxV2NodeFloatView m_closure; // 0x38
	private Buffer[] m_buffers; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x8
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x10
	private static DelegateBridge __Hotfix0_AfterHideEffect; // 0x18
	private static DelegateBridge __Hotfix0_AfterShowEffect; // 0x20
	private static DelegateBridge __Hotfix0_ResetToState; // 0x28
	private static DelegateBridge __Hotfix0_SetBuffer; // 0x30


	// RVA: 0x2562578 VA: 0x7594b7a578
	public Void .ctor(SandboxV2NodeFloatView closure) { }
	// RVA: 0x256263c VA: 0x7594b7a63c
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x2562ac4 VA: 0x7594b7aac4
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x2562f4c VA: 0x7594b7af4c
	protected override Void AfterHideEffect() { }
	// RVA: 0x2562fcc VA: 0x7594b7afcc
	protected override Void AfterShowEffect() { }
	// RVA: 0x256304c VA: 0x7594b7b04c
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x256331c VA: 0x7594b7b31c
	public Void SetBuffer(Int32 index, Buffer buffer) { }
	// RVA: 0x25634c8 VA: 0x7594b7b4c8
	private Void <GenerateTweenOfHide>b__4_1(Single val) { }
	// RVA: 0x25636e0 VA: 0x7594b7b6e0
	private Void <GenerateTweenOfShow>b__5_1(Single val) { }
	// RVA: 0x25638f8 VA: 0x7594b7b8f8
	private Void <>xLuaBaseProxy_AfterHideEffect() { }
	// RVA: 0x2563900 VA: 0x7594b7b900
	private Void <>xLuaBaseProxy_AfterShowEffect() { }
	// RVA: 0x2563908 VA: 0x7594b7b908
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```