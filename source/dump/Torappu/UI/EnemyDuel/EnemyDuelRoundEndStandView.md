# EnemyDuelRoundEndStandView

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `EnemyDuelRoundEndBarView _barView`

- `SimpleLayoutContent _playerList`

- `UIAnimationLocation _anim`

- `PlayerItemAdapter m_adapter`

- `EnemyDuelRoundEndStandViewModel m_cachedModel`

- `Boolean m_hasInitialized`

- `Tween m_tween`


## Methods

- `Void OnStatePause()`

- `Void _InitIfNot()`

- `Void _PlayAnim()`

- `Void <_PlayAnim>b__10_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelRoundEndStandView : DataBinder`1
{
	private EnemyDuelRoundEndBarView _barView; // 0x20
	private SimpleLayoutContent _playerList; // 0x28
	private UIAnimationLocation _anim; // 0x30
	private PlayerItemAdapter m_adapter; // 0x40
	private EnemyDuelRoundEndStandViewModel m_cachedModel; // 0x48
	private Boolean m_hasInitialized; // 0x50
	private Tween m_tween; // 0x58
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_OnStatePause; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__PlayAnim; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2990a00 VA: 0x7594fa8a00
	public override Void OnValueChanged(EnemyDuelRoundEndStandProperty property) { }
	// RVA: 0x2990800 VA: 0x7594fa8800
	public Void OnStatePause() { }
	// RVA: 0x2990b20 VA: 0x7594fa8b20
	private Void _InitIfNot() { }
	// RVA: 0x2990bec VA: 0x7594fa8bec
	private Void _PlayAnim() { }
	// RVA: 0x2990dec VA: 0x7594fa8dec
	public Void .ctor() { }
	// RVA: 0x2990e7c VA: 0x7594fa8e7c
	private Void <_PlayAnim>b__10_0() { }
}
```