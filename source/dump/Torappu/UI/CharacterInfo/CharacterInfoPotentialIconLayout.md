# CharacterInfoPotentialIconLayout

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Single _itemFadeDur`

- `Single _itemFadeMoveBias`

- `CharacterInfoPotentialIconHolder _iconPrefab`

- `Vector2 _gridSize`

- `Rect _padding`

- `Single _spacing`

- `InnerAdapter m_adapter`

- `InnerLayouter m_layouter`

- `Boolean m_hasInited`


## Methods

- `Void UpdateData(IList`1)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoPotentialIconLayout : UICustomAdapterLayout`2
{
	private Single _itemFadeDur; // 0x78
	private Single _itemFadeMoveBias; // 0x7c
	private CharacterInfoPotentialIconHolder _iconPrefab; // 0x80
	private Vector2 _gridSize; // 0x88
	private Rect _padding; // 0x90
	private Single _spacing; // 0xa0
	private List`1 m_iconRankList; // 0xa8
	private Dictionary`2 m_gridIndexMap; // 0xb0
	private InnerAdapter m_adapter; // 0xb8
	private InnerLayouter m_layouter; // 0xc0
	private Boolean m_hasInited; // 0xc8
	private static DelegateBridge __Hotfix0_UpdateData; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2d7d9fc VA: 0x75953959fc
	public Void UpdateData(IList`1 potentialIconList) { }
	// RVA: 0x2d7dcd8 VA: 0x7595395cd8
	private Void _InitIfNot() { }
	// RVA: 0x2d7dfb4 VA: 0x7595395fb4
	public Void .ctor() { }
}
```