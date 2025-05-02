# RoguelikeTopicDifficultyDetailState

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `SimpleLayoutContent _difficultyList`

- `RectTransform _backBtn`

- `RoguelikeTopicDifficultyDetailStateBean m_stateBean`

- `Adapter m_adapter`

- `RoguelikeTopicNormalModelStyle m_normalModeStyle`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void OnBackClick()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicDifficultyDetailState : PopupFloatState
{
	private SimpleLayoutContent _difficultyList; // 0x70
	private RectTransform _backBtn; // 0x78
	private RoguelikeTopicDifficultyDetailStateBean m_stateBean; // 0x80
	private Adapter m_adapter; // 0x88
	private RoguelikeTopicNormalModelStyle m_normalModeStyle; // 0x90
	private Boolean m_isInited; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnBackClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x264cdec VA: 0x7594c64dec
	public override IStateBean GetCacheBean() { }
	// RVA: 0x264ce54 VA: 0x7594c64e54
	private Void _InitIfNot() { }
	// RVA: 0x264cf5c VA: 0x7594c64f5c
	protected override Void OnEnter() { }
	// RVA: 0x264d310 VA: 0x7594c65310
	public Void OnBackClick() { }
	// RVA: 0x264d384 VA: 0x7594c65384
	public Void .ctor() { }
	// RVA: 0x264d430 VA: 0x7594c65430
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```