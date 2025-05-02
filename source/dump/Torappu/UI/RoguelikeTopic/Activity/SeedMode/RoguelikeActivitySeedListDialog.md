# RoguelikeActivitySeedListDialog

**Namespace:** `Torappu.UI.RoguelikeTopic.Activity.SeedMode`


## Fields

- `UIRenderTextureImage _blur`

- `RoguelikeActivitySeedListView _view`

- `RectTransform _backRect`

- `RoguelikeActivitySeedListModel m_cachedModel`


## Methods

- `Void _OnSwitchTypeTab(SeedItemType)`

- `Void _OnApplySeed(String)`

- `Void _SendApplySeedRequest(String)`

- `Void _OnClickCopySeed(String)`

- `Void OnCloseDialog()`

- `Void <_SendApplySeedRequest>b__9_0(RoguelikeTopicSetSeedResponse)`

- `Void <>xLuaBaseProxy_OnInit()`

- `UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.Activity.SeedMode
public class RoguelikeActivitySeedListDialog : UICompDialog`1
{
	private UIRenderTextureImage _blur; // 0x48
	private RoguelikeActivitySeedListView _view; // 0x50
	private RectTransform _backRect; // 0x58
	private RoguelikeActivitySeedListModel m_cachedModel; // 0x60
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge __Hotfix0__OnSwitchTypeTab; // 0x10
	private static DelegateBridge __Hotfix0__OnApplySeed; // 0x18
	private static DelegateBridge __Hotfix0__SendApplySeedRequest; // 0x20
	private static DelegateBridge __Hotfix0__OnClickCopySeed; // 0x28
	private static DelegateBridge __Hotfix0_OnCloseDialog; // 0x30
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x26e0784 VA: 0x7594cf8784
	protected override Void OnInit() { }
	// RVA: 0x26e09a0 VA: 0x7594cf89a0
	protected override Void OnRender(InputParam input) { }
	// RVA: 0x26e11c8 VA: 0x7594cf91c8
	private Void _OnSwitchTypeTab(SeedItemType targetType) { }
	// RVA: 0x26e12f8 VA: 0x7594cf92f8
	private Void _OnApplySeed(String seed) { }
	// RVA: 0x26e1624 VA: 0x7594cf9624
	private Void _SendApplySeedRequest(String seed) { }
	// RVA: 0x26e1890 VA: 0x7594cf9890
	private Void _OnClickCopySeed(String seed) { }
	// RVA: 0x26e193c VA: 0x7594cf993c
	public Void OnCloseDialog() { }
	// RVA: 0x26e1a10 VA: 0x7594cf9a10
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x26e1a78 VA: 0x7594cf9a78
	public Void .ctor() { }
	// RVA: 0x26e1b08 VA: 0x7594cf9b08
	private Void <_SendApplySeedRequest>b__9_0(RoguelikeTopicSetSeedResponse res) { }
	// RVA: 0x26e1c10 VA: 0x7594cf9c10
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x26e1c18 VA: 0x7594cf9c18
	private UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget() { }
}
```