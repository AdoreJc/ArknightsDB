# SquadFriendDetailView

**Namespace:** `Torappu.UI.Squad`


## Fields

- `UIBlurFloatPanel _fullScreenImg`

- `UIStyleProvider _styleProvider`

- `SquadFriendDetailUpperBarView _upperBarView`

- `SquadFriendDetailLowerView _lowerCharInfoView`

- `PlayerAvatarView m_avatarView`

- `SquadAssistData m_cacheData`

- `Boolean m_inited`

- `UIStateFinder m_stateFinder`

- `UIPageFinder m_pageFinder`

- `String m_cachedUid`


## Methods

- `Void _InitIfNot()`

- `Void OnAlreadyRequestClick()`

- `Void OnFriendRequestClick()`

- `Void OnApplyAssistClick()`

- `Void Dismiss()`

- `Void OnFriendAvatarClick()`

- `Void OnCharShowClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class SquadFriendDetailView : DataBinder`1, IHotfixable
{
	private UIBlurFloatPanel _fullScreenImg; // 0x20
	private UIStyleProvider _styleProvider; // 0x28
	private SquadFriendDetailUpperBarView _upperBarView; // 0x30
	private SquadFriendDetailLowerView _lowerCharInfoView; // 0x38
	private PlayerAvatarView m_avatarView; // 0x40
	private SquadAssistData m_cacheData; // 0x48
	private Boolean m_inited; // 0x50
	private UIStateFinder m_stateFinder; // 0x58
	private UIPageFinder m_pageFinder; // 0x68
	private String m_cachedUid; // 0x78
	private List`1 m_createdCharViews; // 0x80
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnAlreadyRequestClick; // 0x8
	private static DelegateBridge __Hotfix0_OnFriendRequestClick; // 0x10
	private static DelegateBridge __Hotfix0_OnApplyAssistClick; // 0x18
	private static DelegateBridge __Hotfix0_Dismiss; // 0x20
	private static DelegateBridge __Hotfix0_OnFriendAvatarClick; // 0x28
	private static DelegateBridge __Hotfix0_OnCharShowClick; // 0x30
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x23c79f4 VA: 0x75949df9f4
	private Void _InitIfNot() { }
	// RVA: 0x23c7b04 VA: 0x75949dfb04
	public Void OnAlreadyRequestClick() { }
	// RVA: 0x23c7bb8 VA: 0x75949dfbb8
	public Void OnFriendRequestClick() { }
	// RVA: 0x23c7cb4 VA: 0x75949dfcb4
	public Void OnApplyAssistClick() { }
	// RVA: 0x23c7d58 VA: 0x75949dfd58
	public Void Dismiss() { }
	// RVA: 0x23c7dfc VA: 0x75949dfdfc
	public Void OnFriendAvatarClick() { }
	// RVA: 0x23c7eec VA: 0x75949dfeec
	public Void OnCharShowClick() { }
	// RVA: 0x23c7f90 VA: 0x75949dff90
	public override Void OnValueChanged(SquadAssistCharDetailProperty property) { }
	// RVA: 0x23c8138 VA: 0x75949e0138
	public Void .ctor() { }
}
```