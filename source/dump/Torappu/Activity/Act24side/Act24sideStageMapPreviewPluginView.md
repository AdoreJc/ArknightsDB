# Act24sideStageMapPreviewPluginView

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `TwoStateToggle _previewPartToggle`

- `Act24sideStageMapPreviewItemView _previewItemPrefab`

- `RectTransform _singlePreviewParent`

- `UIBlurFloatPanel _blurPanel`

- `SimpleLayoutContent _previewList`

- `ScrollViewPager _scrollPager`

- `Text _textCurrent`

- `Text _textTotal`

- `Boolean m_hasInited`

- `PreviewListAdapter m_previewListAdapter`

- `Act24sideStageMapPreviewItemView m_singlePreviewItem`

- `StageData m_stageData`

- `Act24SideData m_actData`


## Methods

- `Void _RenderSinglePreview()`

- `Void _RenderMultiplePreview(List`1)`

- `Void _InitIfNot()`

- `Void _OnPageIndexUpdate(Int32)`

- `Void Hide()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideStageMapPreviewPluginView : StageMapPreviewPluginView
{
	private TwoStateToggle _previewPartToggle; // 0x18
	private Act24sideStageMapPreviewItemView _previewItemPrefab; // 0x20
	private RectTransform _singlePreviewParent; // 0x28
	private UIBlurFloatPanel _blurPanel; // 0x30
	private SimpleLayoutContent _previewList; // 0x38
	private ScrollViewPager _scrollPager; // 0x40
	private Text _textCurrent; // 0x48
	private Text _textTotal; // 0x50
	private RectTransform[] _btnBackRtList; // 0x58
	private Boolean m_hasInited; // 0x60
	private PreviewListAdapter m_previewListAdapter; // 0x68
	private Act24sideStageMapPreviewItemView m_singlePreviewItem; // 0x70
	private StageData m_stageData; // 0x78
	private Act24SideData m_actData; // 0x80
	private static DelegateBridge __Hotfix0_Show; // 0x0
	private static DelegateBridge __Hotfix0_Dispose; // 0x8
	private static DelegateBridge __Hotfix0__RenderSinglePreview; // 0x10
	private static DelegateBridge __Hotfix0__RenderMultiplePreview; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__OnPageIndexUpdate; // 0x28
	private static DelegateBridge __Hotfix0_Hide; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x32e1954 VA: 0x75958f9954
	public override Void Show(String actId, StageData stageData, ILoadAsset assetLoader) { }
	// RVA: 0x32e1f9c VA: 0x75958f9f9c
	public override Void Dispose() { }
	// RVA: 0x32e1e8c VA: 0x75958f9e8c
	private Void _RenderSinglePreview() { }
	// RVA: 0x32e1d74 VA: 0x75958f9d74
	private Void _RenderMultiplePreview(List`1 previewList) { }
	// RVA: 0x32e1afc VA: 0x75958f9afc
	private Void _InitIfNot() { }
	// RVA: 0x32e20f4 VA: 0x75958fa0f4
	private Void _OnPageIndexUpdate(Int32 currentIdx) { }
	// RVA: 0x32e21a0 VA: 0x75958fa1a0
	public Void Hide() { }
	// RVA: 0x32e2214 VA: 0x75958fa214
	public Void .ctor() { }
}
```