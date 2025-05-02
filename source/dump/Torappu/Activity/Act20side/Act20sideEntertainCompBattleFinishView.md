# Act20sideEntertainCompBattleFinishView

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `UIFullScreenImage _imgBlur`

- `Text _txtName`

- `Text _txtPerformanceScore`

- `Text _txtExpressionScore`

- `Text _txtOperationScore`

- `Text _txtTotalScore`

- `UIAtlasImage _imgRank`

- `UIAtlasImage _imgRankAnim`

- `GameObject _panelNewRank`

- `UIAtlasObject _rankImageObject`

- `AnimationWrapper _animationWrapper`

- `Tween m_enterTween`


## Methods

- `Void EventOnViewClicked()`

- `Void _Render(Act20sideEntertainCompBattleFinishViewModel)`

- `Void _Init()`

- `Void _RenderView(Act20sideEntertainCompBattleFinishViewModel)`

- `IEnumerator _PlayEnterAnim()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideEntertainCompBattleFinishView : DynBattleFinishView
{
	private const String ANIM_ENTER; // 0x0
	private UIFullScreenImage _imgBlur; // 0x20
	private Text _txtName; // 0x28
	private Text _txtPerformanceScore; // 0x30
	private Text _txtExpressionScore; // 0x38
	private Text _txtOperationScore; // 0x40
	private Text _txtTotalScore; // 0x48
	private UIAtlasImage _imgRank; // 0x50
	private UIAtlasImage _imgRankAnim; // 0x58
	private GameObject _panelNewRank; // 0x60
	private List`1 _rankImageName; // 0x68
	private UIAtlasObject _rankImageObject; // 0x70
	private AnimationWrapper _animationWrapper; // 0x78
	private Tween m_enterTween; // 0x80
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_EventOnViewClicked; // 0x8
	private static DelegateBridge __Hotfix0__Render; // 0x10
	private static DelegateBridge __Hotfix0__Init; // 0x18
	private static DelegateBridge __Hotfix0__RenderView; // 0x20
	private static DelegateBridge __Hotfix0__PlayEnterAnim; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x32ff884 VA: 0x7595917884
	protected override Void OnInit() { }
	// RVA: 0x32ffbd0 VA: 0x7595917bd0
	public Void EventOnViewClicked() { }
	// RVA: 0x32ffb08 VA: 0x7595917b08
	private Void _Render(Act20sideEntertainCompBattleFinishViewModel viewModel) { }
	// RVA: 0x32ffc58 VA: 0x7595917c58
	private Void _Init() { }
	// RVA: 0x32ffd90 VA: 0x7595917d90
	private Void _RenderView(Act20sideEntertainCompBattleFinishViewModel viewModel) { }
	// RVA: 0x3300110 VA: 0x7595918110
	private IEnumerator _PlayEnterAnim() { }
	// RVA: 0x33001e4 VA: 0x75959181e4
	public Void .ctor() { }
}
```