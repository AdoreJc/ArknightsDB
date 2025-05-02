# SandboxV2EnterAnimTween

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `UIAnimationLocation m_enterAnim`

- `Single <duration>k__BackingField`

- `Single <delay>k__BackingField`

- `Ease <ease>k__BackingField`


## Properties

- `Single duration`

- `Single delay`

- `Ease ease`


## Methods

- `Single get_duration()`

- `Void set_duration(Single)`

- `Single get_delay()`

- `Void set_delay(Single)`

- `Ease get_ease()`

- `Void set_ease(Ease)`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2EnterAnimTween : UISwitchTween
{
	private UIAnimationLocation m_enterAnim; // 0x38
	private Single <duration>k__BackingField; // 0x48
	private Single <delay>k__BackingField; // 0x4c
	private Ease <ease>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0_get_duration; // 0x0
	private static DelegateBridge __Hotfix0_set_duration; // 0x8
	private static DelegateBridge __Hotfix0_get_delay; // 0x10
	private static DelegateBridge __Hotfix0_set_delay; // 0x18
	private static DelegateBridge __Hotfix0_get_ease; // 0x20
	private static DelegateBridge __Hotfix0_set_ease; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x38
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x40
	private static DelegateBridge __Hotfix0_ResetToState; // 0x48

	public Single duration { get; set; }
	public Single delay { get; set; }
	public Ease ease { get; set; }

	// RVA: 0x25b0fbc VA: 0x7594bc8fbc
	public Single get_duration() { }
	// RVA: 0x25b1024 VA: 0x7594bc9024
	public Void set_duration(Single value) { }
	// RVA: 0x25b10a0 VA: 0x7594bc90a0
	public Single get_delay() { }
	// RVA: 0x25b1108 VA: 0x7594bc9108
	public Void set_delay(Single value) { }
	// RVA: 0x25b1184 VA: 0x7594bc9184
	public Ease get_ease() { }
	// RVA: 0x25b11ec VA: 0x7594bc91ec
	public Void set_ease(Ease value) { }
	// RVA: 0x25b1268 VA: 0x7594bc9268
	public Void .ctor(UIAnimationLocation enterAnim) { }
	// RVA: 0x25b1308 VA: 0x7594bc9308
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x25b14e4 VA: 0x7594bc94e4
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x25b168c VA: 0x7594bc968c
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x25b173c VA: 0x7594bc973c
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```