# DeepSeaRPPlaceView

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `UIAtlasImage _imgIcon`

- `UIAtlasImage _imgGreyIcon`

- `UIAtlasImage _imgIconSecondary`

- `UIAtlasObject _mapAtlas`

- `UIAtlasImage _imgLock`

- `UIAtlasImage _imgRank`

- `Text _textName`

- `GameObject _battlePartGo`

- `Text _textStageCode`

- `GameObject _unknowPartGo`

- `GameObject _unknowGlowGo`

- `GameObject _activePartGo`

- `GameObject _greyPartGo`

- `GameObject _trackPointMainGo`

- `GameObject _trackPointSubGo`

- `GameObject _trackPointRingGo`

- `UIAnimationLocation _discoverAnim`

- `UIAnimationLocation _emergeAnim`

- `UIAnimationLocation _switchAnim`

- `UIAnimationLocation _completeAnim`

- `DeepSeaRPNodeModel m_activeNodeModel`

- `DeepSeaRPPlaceModel m_placeModel`

- `DeepSeaRPZoneMapView m_mapView`


## Methods

- `Void Render(DeepSeaRPZoneMapView, DeepSeaRPPlaceModel)`

- `Void _UpdateView(DeepSeaRPPlaceModel)`

- `Void _RenderGreyPart(DeepSeaRPNodeModel)`

- `Void _RenderUnknowPart(DeepSeaRPPlaceModel)`

- `Void _RenderActivePart(DeepSeaRPNodeModel)`

- `Void _PlaySwitchAnim(DeepSeaRPNodeModel, Action)`

- `Void _PlayCompleteAnim(Boolean, DeepSeaRPNodeModel, Action)`

- `Void _PlayDiscoverAnim(Action)`

- `Void _PlayEmergeAnim(Action)`

- `Void OnNodeClick()`

- `Void OnPlaceDiscovered()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPPlaceView : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _imgIcon; // 0x18
	private UIAtlasImage _imgGreyIcon; // 0x20
	private UIAtlasImage _imgIconSecondary; // 0x28
	private UIAtlasObject _mapAtlas; // 0x30
	private UIAtlasImage _imgLock; // 0x38
	private UIAtlasImage _imgRank; // 0x40
	private Text _textName; // 0x48
	private GameObject _battlePartGo; // 0x50
	private Text _textStageCode; // 0x58
	private GameObject _unknowPartGo; // 0x60
	private GameObject _unknowGlowGo; // 0x68
	private GameObject _activePartGo; // 0x70
	private GameObject _greyPartGo; // 0x78
	private GameObject _trackPointMainGo; // 0x80
	private GameObject _trackPointSubGo; // 0x88
	private GameObject _trackPointRingGo; // 0x90
	private UIAnimationLocation _discoverAnim; // 0x98
	private UIAnimationLocation _emergeAnim; // 0xa8
	private UIAnimationLocation _switchAnim; // 0xb8
	private UIAnimationLocation _completeAnim; // 0xc8
	private Nullable`1 m_cachedPlaceStatus; // 0xd8
	private Nullable`1 m_cachedNodeType; // 0xe0
	private Nullable`1 m_cachedGreyStatus; // 0xe8
	private DeepSeaRPNodeModel m_activeNodeModel; // 0xf0
	private DeepSeaRPPlaceModel m_placeModel; // 0xf8
	private DeepSeaRPZoneMapView m_mapView; // 0x100
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__UpdateView; // 0x8
	private static DelegateBridge __Hotfix0__RenderGreyPart; // 0x10
	private static DelegateBridge __Hotfix0__RenderUnknowPart; // 0x18
	private static DelegateBridge __Hotfix0__RenderActivePart; // 0x20
	private static DelegateBridge __Hotfix0__PlaySwitchAnim; // 0x28
	private static DelegateBridge __Hotfix0__PlayCompleteAnim; // 0x30
	private static DelegateBridge __Hotfix0__PlayDiscoverAnim; // 0x38
	private static DelegateBridge __Hotfix0__PlayEmergeAnim; // 0x40
	private static DelegateBridge __Hotfix0_OnNodeClick; // 0x48
	private static DelegateBridge __Hotfix0_OnPlaceDiscovered; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x29c7f88 VA: 0x7594fdff88
	public Void Render(DeepSeaRPZoneMapView mapView, DeepSeaRPPlaceModel placeModel) { }
	// RVA: 0x29c8be0 VA: 0x7594fe0be0
	private Void _UpdateView(DeepSeaRPPlaceModel placeModel) { }
	// RVA: 0x29c92a8 VA: 0x7594fe12a8
	private Void _RenderGreyPart(DeepSeaRPNodeModel activeNodeModel) { }
	// RVA: 0x29c8e2c VA: 0x7594fe0e2c
	private Void _RenderUnknowPart(DeepSeaRPPlaceModel placeModel) { }
	// RVA: 0x29c8ee8 VA: 0x7594fe0ee8
	private Void _RenderActivePart(DeepSeaRPNodeModel activeNodeModel) { }
	// RVA: 0x29c89c4 VA: 0x7594fe09c4
	private Void _PlaySwitchAnim(DeepSeaRPNodeModel activeNodeModel, Action onComplete) { }
	// RVA: 0x29c86e0 VA: 0x7594fe06e0
	private Void _PlayCompleteAnim(Boolean isInverse, DeepSeaRPNodeModel activeNodeModel, Action onComplete) { }
	// RVA: 0x29c8548 VA: 0x7594fe0548
	private Void _PlayDiscoverAnim(Action onComplete) { }
	// RVA: 0x29c83a0 VA: 0x7594fe03a0
	private Void _PlayEmergeAnim(Action onComplete) { }
	// RVA: 0x29c93bc VA: 0x7594fe13bc
	public Void OnNodeClick() { }
	// RVA: 0x29c951c VA: 0x7594fe151c
	public Void OnPlaceDiscovered() { }
	// RVA: 0x29c9660 VA: 0x7594fe1660
	public Void .ctor() { }
}
```