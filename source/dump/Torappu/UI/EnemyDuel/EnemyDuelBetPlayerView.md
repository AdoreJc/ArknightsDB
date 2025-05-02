# EnemyDuelBetPlayerView

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `UIAnimationLocation _showAnim`

- `Image _imgPlayerIcon`

- `Text _textWinStreak`

- `GameObject _pnlWinStreak`

- `PnlBkg _pnlSelf`

- `PnlBkg _pnlOther`

- `Single m_showPos`

- `String m_cachedAvatarId`

- `PlayerAvatarType m_cachedAvatarType`

- `AvatarCharType m_cachedAvatarCharType`

- `UIStateFinder m_stateFinder`

- `Boolean m_inited`


## Properties

- `Single showPos`


## Methods

- `Single get_showPos()`

- `Void _InitIfNot()`

- `Void SetShowPos(Single)`

- `Void Render(EnemyDuelBetPlayerViewModel, EnemyDuelModeType, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelBetPlayerView : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation _showAnim; // 0x18
	private Image _imgPlayerIcon; // 0x28
	private Text _textWinStreak; // 0x30
	private GameObject _pnlWinStreak; // 0x38
	private PnlBkg _pnlSelf; // 0x40
	private PnlBkg _pnlOther; // 0x48
	private Single m_showPos; // 0x50
	private String m_cachedAvatarId; // 0x58
	private PlayerAvatarType m_cachedAvatarType; // 0x60
	private AvatarCharType m_cachedAvatarCharType; // 0x64
	private UIStateFinder m_stateFinder; // 0x68
	private Boolean m_inited; // 0x78
	private static DelegateBridge __Hotfix0_get_showPos; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_SetShowPos; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Single showPos { get; }

	// RVA: 0x2979fb8 VA: 0x7594f91fb8
	public Single get_showPos() { }
	// RVA: 0x297a028 VA: 0x7594f92028
	private Void _InitIfNot() { }
	// RVA: 0x297a0c8 VA: 0x7594f920c8
	public Void SetShowPos(Single pos) { }
	// RVA: 0x297a18c VA: 0x7594f9218c
	public Void Render(EnemyDuelBetPlayerViewModel viewModel, EnemyDuelModeType modeType, String actId) { }
	// RVA: 0x297a4c4 VA: 0x7594f924c4
	public Void .ctor() { }
}
```