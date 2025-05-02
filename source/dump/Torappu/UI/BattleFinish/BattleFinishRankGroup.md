# BattleFinishRankGroup

**Namespace:** `Torappu.UI.BattleFinish`


## Fields

- `PlayerBattleRank m_rankCache`

- `Boolean m_isInited`


## Properties

- `PlayerBattleRank rank`


## Methods

- `Void set_rank(PlayerBattleRank)`

- `Void _Render(PlayerBattleRank)`

- `IEnumerator _RenderCor(PlayerBattleRank)`

- `Void _PlayStarPopupSE()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BattleFinish
public class BattleFinishRankGroup : MonoBehaviour
{
	private TwoStateToggle[] _rankSymbols; // 0x18
	private PlayerBattleRank m_rankCache; // 0x20
	private Boolean m_isInited; // 0x24

	public PlayerBattleRank rank { set; }

	// RVA: 0x2e8f8e4 VA: 0x75954a78e4
	public Void set_rank(PlayerBattleRank value) { }
	// RVA: 0x2e93b38 VA: 0x75954abb38
	private Void _Render(PlayerBattleRank rank) { }
	// RVA: 0x2e93bb0 VA: 0x75954abbb0
	private IEnumerator _RenderCor(PlayerBattleRank rank) { }
	// RVA: 0x2e93c5c VA: 0x75954abc5c
	private Void _PlayStarPopupSE() { }
	// RVA: 0x2e93cc8 VA: 0x75954abcc8
	public Void .ctor() { }
}
```