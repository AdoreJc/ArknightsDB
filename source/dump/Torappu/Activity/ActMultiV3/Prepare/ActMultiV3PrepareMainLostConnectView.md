# ActMultiV3PrepareMainLostConnectView

**Namespace:** `Torappu.Activity.ActMultiV3.Prepare`


## Fields

- `UIAnimationLocation _entryAnim`

- `UIAnimationLocation _loopAnim`

- `Tween m_entryAnimTween`


## Methods

- `Void UpdatePing(Int32)`

- `Void _EntryAnimDone()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.Prepare
public class ActMultiV3PrepareMainLostConnectView : ActMultiV3PrepareMainFadeViewBase, IPingListener
{
	private UIAnimationLocation _entryAnim; // 0x30
	private UIAnimationLocation _loopAnim; // 0x40
	private Tween m_entryAnimTween; // 0x50
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_UpdatePing; // 0x8
	private static DelegateBridge __Hotfix0__EntryAnimDone; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x31635e8 VA: 0x759577b5e8
	public override Void OnValueChanged(ActMultiV3PrepareMainViewModelProperty property) { }
	// RVA: 0x3163660 VA: 0x759577b660
	public Void UpdatePing(Int32 ping) { }
	// RVA: 0x3163888 VA: 0x759577b888
	private Void _EntryAnimDone() { }
	// RVA: 0x3163914 VA: 0x759577b914
	public Void .ctor() { }
}
```