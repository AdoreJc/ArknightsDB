# PlayerAvatarView

**Namespace:** `Torappu.UI`


## Fields

- `RectTransform _dynAvatarContainer`

- `GameObject _staticAvatarRoot`

- `Image _staticAvatarSprite`

- `UIColorGraphic _colorGraphic`

- `PlayerUIAvatarViewModel m_avatarViewModel`

- `PlayerDynAvatarView m_dynAvatarView`

- `UIPageFinder m_pageFinder`

- `String m_cacheDynAvatarId`

- `Boolean m_hasInited`


## Properties

- `UIColorGraphic colorGraphic`


## Methods

- `UIColorGraphic get_colorGraphic()`

- `Void Render(AvatarInfo, ILoadAsset)`

- `Void Render(AvatarInfo, Params, ILoadAsset)`

- `Void Render(PlayerAvatarItemViewModel, ILoadAsset)`

- `Void Render(PlayerAvatarItemViewModel, Params, ILoadAsset)`

- `Void _Render(Params, ILoadAsset)`

- `Boolean _TryLoadDynAvatar(String)`

- `Boolean _BattleFinishOnlyTryLoadDynAvatar(String)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class PlayerAvatarView : MonoBehaviour, IHotfixable
{
	private const Single DYN_AVATAR_SCALE; // 0x0
	private RectTransform _dynAvatarContainer; // 0x18
	private GameObject _staticAvatarRoot; // 0x20
	private Image _staticAvatarSprite; // 0x28
	private UIColorGraphic _colorGraphic; // 0x30
	private PlayerUIAvatarViewModel m_avatarViewModel; // 0x38
	private PlayerDynAvatarView m_dynAvatarView; // 0x40
	private UIPageFinder m_pageFinder; // 0x48
	private String m_cacheDynAvatarId; // 0x58
	private Boolean m_hasInited; // 0x60
	private static DelegateBridge __Hotfix0_get_colorGraphic; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix1_Render; // 0x10
	private static DelegateBridge __Hotfix2_Render; // 0x18
	private static DelegateBridge __Hotfix3_Render; // 0x20
	private static DelegateBridge __Hotfix0__Render; // 0x28
	private static DelegateBridge __Hotfix0__TryLoadDynAvatar; // 0x30
	private static DelegateBridge __Hotfix0__BattleFinishOnlyTryLoadDynAvatar; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public UIColorGraphic colorGraphic { get; }

	// RVA: 0x2276f84 VA: 0x759488ef84
	public UIColorGraphic get_colorGraphic() { }
	// RVA: 0x2276fec VA: 0x759488efec
	public Void Render(AvatarInfo avatarInfo, ILoadAsset spriteLoader) { }
	// RVA: 0x22770a8 VA: 0x759488f0a8
	public Void Render(AvatarInfo avatarInfo, Params param, ILoadAsset spriteLoader) { }
	// RVA: 0x227728c VA: 0x759488f28c
	public Void Render(PlayerAvatarItemViewModel model, ILoadAsset sprietLoader) { }
	// RVA: 0x2277348 VA: 0x759488f348
	public Void Render(PlayerAvatarItemViewModel model, Params param, ILoadAsset spriteLoader) { }
	// RVA: 0x2277160 VA: 0x759488f160
	private Void _Render(Params param, ILoadAsset spriteLoader) { }
	// RVA: 0x2277778 VA: 0x759488f778
	private Boolean _TryLoadDynAvatar(String dynAvatarId) { }
	// RVA: 0x22774a0 VA: 0x759488f4a0
	private Boolean _BattleFinishOnlyTryLoadDynAvatar(String dynAvatarId) { }
	// RVA: 0x2277400 VA: 0x759488f400
	private Void _InitIfNot() { }
	// RVA: 0x2277a64 VA: 0x759488fa64
	public Void .ctor() { }
}
```