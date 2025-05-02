# Act5D0MileStoneItemObj

**Namespace:** `Torappu.Activity.Act5D0`


## Fields

- `Image _bgEff`

- `Image _bg`

- `Button _ableToGetButton`

- `Text _indexText`

- `Text _itemName`

- `Text _detailText`

- `Image _countSymbol`

- `Text _countText`

- `GameObject _finishPart`

- `GameObject _contentRoot`

- `GameObject _gapRoot`

- `CanvasGroup _group`

- `Image _completeMark`

- `Text _desc`

- `CanvasGroup _canvasGroup`

- `GameObject _replicateFlag`

- `Tween m_cacheTween`


## Methods

- `Void <>xLuaBaseProxy_InitData(MileStoneViewModel)`

- `Void <>xLuaBaseProxy_OnRenderDataPart(MileStoneViewModel)`

- `Void <>xLuaBaseProxy_OnRenderItemStyle(PartType, State)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D0
public class Act5D0MileStoneItemObj : MileStoneItem
{
	private Image _bgEff; // 0x48
	private Image _bg; // 0x50
	private Button _ableToGetButton; // 0x58
	private Text _indexText; // 0x60
	private Text _itemName; // 0x68
	private Text _detailText; // 0x70
	private Image _countSymbol; // 0x78
	private Text _countText; // 0x80
	private GameObject _finishPart; // 0x88
	private GameObject _contentRoot; // 0x90
	private GameObject _gapRoot; // 0x98
	private CanvasGroup _group; // 0xa0
	private Image _completeMark; // 0xa8
	private Text _desc; // 0xb0
	private CanvasGroup _canvasGroup; // 0xb8
	private GameObject _replicateFlag; // 0xc0
	private Tween m_cacheTween; // 0xc8
	private const Single ANIMATION_ALPHA_SPEED; // 0x0
	private const Single ANIMATION_ANIM_SPEED; // 0x0
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_OnRenderDataPart; // 0x8
	private static DelegateBridge __Hotfix0_OnRenderItemStyle; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x31bfd0c VA: 0x75957d7d0c
	public override Void InitData(MileStoneViewModel viewModel) { }
	// RVA: 0x31c0174 VA: 0x75957d8174
	protected override Void OnRenderDataPart(MileStoneViewModel viewModel) { }
	// RVA: 0x31c03c0 VA: 0x75957d83c0
	protected override Void OnRenderItemStyle(PartType part, State state) { }
	// RVA: 0x31c07b8 VA: 0x75957d87b8
	public Void .ctor() { }
	// RVA: 0x31c0828 VA: 0x75957d8828
	private Void <>xLuaBaseProxy_InitData(MileStoneViewModel P0) { }
	// RVA: 0x31c0830 VA: 0x75957d8830
	private Void <>xLuaBaseProxy_OnRenderDataPart(MileStoneViewModel P0) { }
	// RVA: 0x31c0838 VA: 0x75957d8838
	private Void <>xLuaBaseProxy_OnRenderItemStyle(PartType P0, State P1) { }
}
```