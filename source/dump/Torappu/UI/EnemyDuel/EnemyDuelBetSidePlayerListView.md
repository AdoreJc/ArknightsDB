# EnemyDuelBetSidePlayerListView

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `EnemyDuelBetPlayerView _prefabPlayerView`

- `Vector2 _gridSize`

- `Vector2 _spacing`

- `Rect _padding`

- `Single _showDuration`

- `EaseType _showEase`

- `EnemyDuelBetViewModel m_cachedViewModel`

- `InnerLayouter m_layouter`

- `InnerAdapter m_adapter`

- `Boolean m_inited`


## Methods

- `Void _InitIfNot()`

- `Void Render(List`1, EnemyDuelBetViewModel, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelBetSidePlayerListView : UICustomAdapterLayout`2
{
	private EnemyDuelBetPlayerView _prefabPlayerView; // 0x78
	private Vector2 _gridSize; // 0x80
	private Vector2 _spacing; // 0x88
	private Rect _padding; // 0x90
	private Single _showDuration; // 0xa0
	private EaseType _showEase; // 0xa4
	private List`1 m_cachedPlayerList; // 0xa8
	private EnemyDuelBetViewModel m_cachedViewModel; // 0xb0
	private InnerLayouter m_layouter; // 0xb8
	private InnerAdapter m_adapter; // 0xc0
	private Boolean m_inited; // 0xc8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x297a5a4 VA: 0x7594f925a4
	private Void _InitIfNot() { }
	// RVA: 0x297a86c VA: 0x7594f9286c
	public Void Render(List`1 playerList, EnemyDuelBetViewModel viewModel, Boolean isInit) { }
	// RVA: 0x297a948 VA: 0x7594f92948
	public Void .ctor() { }
}
```