# EnemyDuelBetTopBarEmoticonBtn

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `GameObject _pnlCooldown`

- `GameObject _pnlDisabled`

- `GameObject _pnlAvailable`

- `Text _textCooldown`

- `Image _imgDefaultEmoticonId`

- `EnemyDuelTopBarViewModel m_cachedTopBarViewModel`

- `String m_cachedEmoticonGroupId`

- `String m_cachedEmoticonPicId`

- `Boolean m_inited`

- `EnemyDuelBattleCoolDownController m_coolDownController`

- `UIPageFinder m_pageFinder`


## Methods

- `Void _InitIfNot()`

- `Void Start()`

- `Void OnDestroy()`

- `Void UpdateTime(Single)`

- `Void Render(EnemyDuelTopBarViewModel)`

- `Void _Refresh()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelBetTopBarEmoticonBtn : MonoBehaviour, IHotfixable, ITimeWatcher
{
	private GameObject _pnlCooldown; // 0x18
	private GameObject _pnlDisabled; // 0x20
	private GameObject _pnlAvailable; // 0x28
	private Text _textCooldown; // 0x30
	private Image _imgDefaultEmoticonId; // 0x38
	private EnemyDuelTopBarViewModel m_cachedTopBarViewModel; // 0x40
	private String m_cachedEmoticonGroupId; // 0x48
	private String m_cachedEmoticonPicId; // 0x50
	private Boolean m_inited; // 0x58
	private EnemyDuelBattleCoolDownController m_coolDownController; // 0x60
	private UIPageFinder m_pageFinder; // 0x68
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Start; // 0x8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x10
	private static DelegateBridge __Hotfix0_UpdateTime; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0__Refresh; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x297eb0c VA: 0x7594f96b0c
	private Void _InitIfNot() { }
	// RVA: 0x297ebdc VA: 0x7594f96bdc
	private Void Start() { }
	// RVA: 0x297ec4c VA: 0x7594f96c4c
	private Void OnDestroy() { }
	// RVA: 0x297ecbc VA: 0x7594f96cbc
	public Void UpdateTime(Single timeDelta) { }
	// RVA: 0x297f048 VA: 0x7594f97048
	public Void Render(EnemyDuelTopBarViewModel viewModel) { }
	// RVA: 0x297ed38 VA: 0x7594f96d38
	private Void _Refresh() { }
	// RVA: 0x297f200 VA: 0x7594f97200
	public Void .ctor() { }
}
```