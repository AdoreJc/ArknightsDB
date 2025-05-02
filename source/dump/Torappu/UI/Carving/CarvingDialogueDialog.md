# CarvingDialogueDialog

**Namespace:** `Torappu.UI.Carving`


## Fields

- `GameObject _panelBlur`

- `UIRenderTextureImage _blurBackground`

- `Image _imgCharAvatar`

- `Text _textName`

- `AVGTypeWriterText _textContent`

- `CanvasGroup _canvasGroup`

- `UIAnimationLocation _enterAnim`

- `UIAnimationLocation _loopAnim`

- `RectTransform _backBtn`

- `Boolean m_hasInited`

- `Act35SideDialogueGroupData m_dialogueGroupData`

- `String m_cachedActId`

- `Int32 m_cachedCurrIndex`

- `Tween m_loopAnim`

- `String m_cachedParam`


## Properties

- `Int32 dialogueCount`

- `Boolean isPlayingComplete`


## Methods

- `Int32 get_dialogueCount()`

- `Boolean get_isPlayingComplete()`

- `Void OnClick()`

- `Void _InitIfNot()`

- `Void _PlayNextDialogue()`

- `Void _ConfirmAndClose()`

- `Void <>xLuaBaseProxy_OnInit()`

- `UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget()`

- `UISwitchTween <>xLuaBaseProxy_GenerateShowTween()`

- `Void <>xLuaBaseProxy_OnDestroySubClass()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingDialogueDialog : UICompDialog`1, IHotfixable
{
	private GameObject _panelBlur; // 0x48
	private UIRenderTextureImage _blurBackground; // 0x50
	private NameBgConfig[] _nameBgConfig; // 0x58
	private Image _imgCharAvatar; // 0x60
	private Text _textName; // 0x68
	private AVGTypeWriterText _textContent; // 0x70
	private CanvasGroup _canvasGroup; // 0x78
	private UIAnimationLocation _enterAnim; // 0x80
	private UIAnimationLocation _loopAnim; // 0x90
	private RectTransform _backBtn; // 0xa0
	private Boolean m_hasInited; // 0xa8
	private Act35SideDialogueGroupData m_dialogueGroupData; // 0xb0
	private String m_cachedActId; // 0xb8
	private Int32 m_cachedCurrIndex; // 0xc0
	private Tween m_loopAnim; // 0xc8
	private String m_cachedParam; // 0xd0
	private static DelegateBridge __Hotfix0_get_dialogueCount; // 0x0
	private static DelegateBridge __Hotfix0_get_isPlayingComplete; // 0x8
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge __Hotfix0_OnRender; // 0x18
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x20
	private static DelegateBridge __Hotfix0_GenerateShowTween; // 0x28
	private static DelegateBridge __Hotfix0_OnDestroySubClass; // 0x30
	private static DelegateBridge __Hotfix0_OnClick; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge __Hotfix0__PlayNextDialogue; // 0x48
	private static DelegateBridge __Hotfix0__ConfirmAndClose; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	private Int32 dialogueCount { get; }
	private Boolean isPlayingComplete { get; }

	// RVA: 0x2d8fe74 VA: 0x75953a7e74
	private Int32 get_dialogueCount() { }
	// RVA: 0x2d8ff0c VA: 0x75953a7f0c
	private Boolean get_isPlayingComplete() { }
	// RVA: 0x2d8ffa8 VA: 0x75953a7fa8
	protected override Void OnInit() { }
	// RVA: 0x2d901ac VA: 0x75953a81ac
	protected override Void OnRender(Options input) { }
	// RVA: 0x2d90514 VA: 0x75953a8514
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x2d9057c VA: 0x75953a857c
	public override UISwitchTween GenerateShowTween() { }
	// RVA: 0x2d906b4 VA: 0x75953a86b4
	protected override Void OnDestroySubClass() { }
	// RVA: 0x2d90760 VA: 0x75953a8760
	public Void OnClick() { }
	// RVA: 0x2d90138 VA: 0x75953a8138
	private Void _InitIfNot() { }
	// RVA: 0x2d9031c VA: 0x75953a831c
	private Void _PlayNextDialogue() { }
	// RVA: 0x2d90814 VA: 0x75953a8814
	private Void _ConfirmAndClose() { }
	// RVA: 0x2d9095c VA: 0x75953a895c
	public Void .ctor() { }
	// RVA: 0x2d909ec VA: 0x75953a89ec
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x2d909f4 VA: 0x75953a89f4
	private UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget() { }
	// RVA: 0x2d909fc VA: 0x75953a89fc
	private UISwitchTween <>xLuaBaseProxy_GenerateShowTween() { }
	// RVA: 0x2d90a04 VA: 0x75953a8a04
	private Void <>xLuaBaseProxy_OnDestroySubClass() { }
}
```