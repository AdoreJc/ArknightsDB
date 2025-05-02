# RoguelikeTotemBuffState

**Namespace:** `Torappu.UI.Roguelike.TotemBuff`


## Fields

- `RectTransform _viewContainer`

- `Boolean m_hasInited`

- `RoguelikeDungeonPage m_page`

- `String m_topicId`

- `AbstractRoguelikeTotemBuffView m_totemBuffView`

- `IRoguelikeTotemBuffViewModel m_totemViewModel`

- `MenuAdapter m_menuAdapter`


## Methods

- `Void DismissSelfWithFastMode()`

- `Void ReloadDungeon()`

- `Void _InitIfNot()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.TotemBuff
public class RoguelikeTotemBuffState : PopupFadeState
{
	private RectTransform _viewContainer; // 0x70
	private Boolean m_hasInited; // 0x78
	private RoguelikeDungeonPage m_page; // 0x80
	private String m_topicId; // 0x88
	private AbstractRoguelikeTotemBuffView m_totemBuffView; // 0x90
	private IRoguelikeTotemBuffViewModel m_totemViewModel; // 0x98
	private MenuAdapter m_menuAdapter; // 0xa0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_DismissSelfWithFastMode; // 0x18
	private static DelegateBridge __Hotfix0_ReloadDungeon; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2afa8d8 VA: 0x75951128d8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2afa93c VA: 0x759511293c
	protected override Void OnEnter() { }
	// RVA: 0x2afada0 VA: 0x7595112da0
	protected override Void OnResume() { }
	// RVA: 0x2afae6c VA: 0x7595112e6c
	public Void DismissSelfWithFastMode() { }
	// RVA: 0x2afb00c VA: 0x759511300c
	public Void ReloadDungeon() { }
	// RVA: 0x2afac34 VA: 0x7595112c34
	private Void _InitIfNot() { }
	// RVA: 0x2afb170 VA: 0x7595113170
	public Void .ctor() { }
	// RVA: 0x2afb1e0 VA: 0x75951131e0
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2afb1e8 VA: 0x75951131e8
	private Void <>xLuaBaseProxy_OnResume() { }
}
```