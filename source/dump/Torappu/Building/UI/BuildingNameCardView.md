# BuildingNameCardView

**Namespace:** `Torappu.Building.UI`


## Fields

- `Image _imageBG`

- `RectTransform _avatarContainer`

- `Text _textVisitorName`

- `Text _textUid`

- `Text _textVisitorLevel`

- `UIColorGraphic _colorGraphic`

- `UIScaler _uiScaler`

- `UIPageFinder m_pageFinder`

- `PlayerAvatarView m_avatar`

- `Boolean m_hasInited`


## Methods

- `Void Render(PayloadMessageBoardThisWeekVisitor)`

- `Void Render(RoomOwner)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class BuildingNameCardView : UIStylerApplier`1
{
	private Image _imageBG; // 0x20
	private RectTransform _avatarContainer; // 0x28
	private Text _textVisitorName; // 0x30
	private Text _textUid; // 0x38
	private Text _textVisitorLevel; // 0x40
	private UIColorGraphic _colorGraphic; // 0x48
	private UIScaler _uiScaler; // 0x50
	private UIPageFinder m_pageFinder; // 0x58
	private PlayerAvatarView m_avatar; // 0x68
	private Boolean m_hasInited; // 0x70
	private static DelegateBridge __Hotfix0_OnApplyStyle; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix1_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3d38ca0 VA: 0x7596350ca0
	protected override Void OnApplyStyle(NameCardV2SkinStyle style) { }
	// RVA: 0x3d38d40 VA: 0x7596350d40
	public Void Render(PayloadMessageBoardThisWeekVisitor visitorData) { }
	// RVA: 0x3d39120 VA: 0x7596351120
	public Void Render(RoomOwner visitorData) { }
	// RVA: 0x3d38f6c VA: 0x7596350f6c
	private Void _InitIfNot() { }
	// RVA: 0x3d392e8 VA: 0x75963512e8
	public Void .ctor() { }
}
```