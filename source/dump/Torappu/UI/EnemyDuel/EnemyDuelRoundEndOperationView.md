# EnemyDuelRoundEndOperationView

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `UIAnimationLocation _entryAnim`

- `EnemyDuelRoundEndBarView _barView`

- `Tween m_entryTween`

- `AnimationSwitchTween m_windowTween`

- `UIStateFinder m_stateFinder`


## Methods

- `Void OnStatePause()`

- `Void _PlayEntryTween()`

- `Void <_PlayEntryTween>b__8_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelRoundEndOperationView : DataBinder`1
{
	private UIAnimationLocation _entryAnim; // 0x20
	private EnemyDuelRoundEndBarView _barView; // 0x30
	private EnemyDuelOperationRankItemView[] _itemList; // 0x38
	private Tween m_entryTween; // 0x40
	private AnimationSwitchTween m_windowTween; // 0x48
	private UIStateFinder m_stateFinder; // 0x50
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_OnStatePause; // 0x8
	private static DelegateBridge __Hotfix0__PlayEntryTween; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x298e9d4 VA: 0x7594fa69d4
	public override Void OnValueChanged(EnemyDuelRoundEndOperationProperty property) { }
	// RVA: 0x298e7d4 VA: 0x7594fa67d4
	public Void OnStatePause() { }
	// RVA: 0x298ecb0 VA: 0x7594fa6cb0
	private Void _PlayEntryTween() { }
	// RVA: 0x298ee3c VA: 0x7594fa6e3c
	public Void .ctor() { }
	// RVA: 0x298eecc VA: 0x7594fa6ecc
	private Void <_PlayEntryTween>b__8_0() { }
}
```