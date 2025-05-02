# NewCompletePanel

**Namespace:** ` `


## Fields

- `UIBlurFloatPanel _blurBkg`

- `Text _txtBefore`

- `Text _txtAfter`

- `Single _itemScaleFactor`

- `UIAnimationLocation _animNewCompleteEnter`

- `GameObject _objNewCompletePanel`

- `Tween m_tweener`


## Methods

- `Void Render(CrisisV2SettleViewModel)`

- `Void HidePanel()`

- `Void PlayNewCompleteEnterAnim(TweenCallback)`

- `Void JumpToNewCompleteEnterAnimLastFrame(Coroutine)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class NewCompletePanel : IHotfixable
{
	private UIBlurFloatPanel _blurBkg; // 0x10
	private Text _txtBefore; // 0x18
	private Text _txtAfter; // 0x20
	private Single _itemScaleFactor; // 0x28
	private UIAnimationLocation _animNewCompleteEnter; // 0x30
	private GameObject _objNewCompletePanel; // 0x40
	private Tween m_tweener; // 0x48
	private const String NEW_COMPLETE_ANIM; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_HidePanel; // 0x8
	private static DelegateBridge __Hotfix0_PlayNewCompleteEnterAnim; // 0x10
	private static DelegateBridge __Hotfix0_JumpToNewCompleteEnterAnimLastFrame; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2bd324c VA: 0x75951eb24c
	public Void Render(CrisisV2SettleViewModel viewModel) { }
	// RVA: 0x2bd17d0 VA: 0x75951e97d0
	public Void HidePanel() { }
	// RVA: 0x2bd3358 VA: 0x75951eb358
	public Void PlayNewCompleteEnterAnim(TweenCallback onNewCompleteAnimPlayFinish) { }
	// RVA: 0x2bd228c VA: 0x75951ea28c
	public Void JumpToNewCompleteEnterAnimLastFrame(Coroutine coroutineWithTimeTracer) { }
	// RVA: 0x2bd33dc VA: 0x75951eb3dc
	public Void .ctor() { }
}
```