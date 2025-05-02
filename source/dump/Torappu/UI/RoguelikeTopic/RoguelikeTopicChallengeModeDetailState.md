# RoguelikeTopicChallengeModeDetailState

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `RectTransform _viewHolder`

- `RectTransform _backBtn`

- `String m_cachedTopicId`

- `RoguelikeTopicChallengeModeDetailViewBase m_detailView`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void OnBackClick()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicChallengeModeDetailState : PopupFloatState
{
	private RectTransform _viewHolder; // 0x70
	private RectTransform _backBtn; // 0x78
	private String m_cachedTopicId; // 0x80
	private RoguelikeTopicChallengeModeDetailViewBase m_detailView; // 0x88
	private Boolean m_isInited; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnBackClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x26471f4 VA: 0x7594c5f1f4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2647258 VA: 0x7594c5f258
	private Void _InitIfNot() { }
	// RVA: 0x2647360 VA: 0x7594c5f360
	protected override Void OnEnter() { }
	// RVA: 0x264771c VA: 0x7594c5f71c
	public Void OnBackClick() { }
	// RVA: 0x2647790 VA: 0x7594c5f790
	public Void .ctor() { }
	// RVA: 0x2647800 VA: 0x7594c5f800
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```