# SandboxV2NodeView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `UIAtlasImage _imgNodeBkg`

- `Image _imgNodeIcon`

- `Image _imgWeatherIcon`

- `Text _textNodeType`

- `Text _textNodeName`

- `GameObject _pnlNodeDetail`

- `GameObject _pnlNodeUpgrade`

- `UIColorGraphic _colorGraphic`

- `SimpleLayoutContent _dropList`

- `UIAnimationLocation _enterAnim`

- `Adapter m_adapter`

- `String m_cachedWeatherId`

- `SandboxV2NodeAppearanceType m_cachedAppearanceType`


## Methods

- `Void _RenderAppearanceType(SandboxV2DungeonNodeViewModel, SandboxV2DungeonViewModel)`

- `Void _RenderWeatherIcon(SandboxV2DungeonNodeViewModel, SandboxV2DungeonViewModel)`

- `Void <>xLuaBaseProxy_DoOnInit()`

- `Void <>xLuaBaseProxy_DoOnRecycle()`

- `Void <>xLuaBaseProxy_DoRenderBasicData(SandboxV2DungeonNodeViewModel, SandboxV2DungeonViewModel)`

- `Void <>xLuaBaseProxy_DoRenderData(SandboxV2DungeonNodeViewModel, SandboxV2DungeonViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2NodeView : SandboxV2AbstractNodeView
{
	private const Single NODE_ICON_ALPHA_COMPLETE; // 0x0
	private UIAtlasImage _imgNodeBkg; // 0xe8
	private Image _imgNodeIcon; // 0xf0
	private Image _imgWeatherIcon; // 0xf8
	private Text _textNodeType; // 0x100
	private Text _textNodeName; // 0x108
	private GameObject _pnlNodeDetail; // 0x110
	private GameObject _pnlNodeUpgrade; // 0x118
	private UIColorGraphic _colorGraphic; // 0x120
	private List`1 _upgradeIcons; // 0x128
	private SimpleLayoutContent _dropList; // 0x130
	private UIAnimationLocation _enterAnim; // 0x138
	private Adapter m_adapter; // 0x148
	private String m_cachedWeatherId; // 0x150
	private SandboxV2NodeAppearanceType m_cachedAppearanceType; // 0x158
	private List`1 m_cachedMapDropPreview; // 0x160
	private static DelegateBridge __Hotfix0_DoOnInit; // 0x0
	private static DelegateBridge __Hotfix0_DoOnRecycle; // 0x8
	private static DelegateBridge __Hotfix0_DoRenderBasicData; // 0x10
	private static DelegateBridge __Hotfix0_DoRenderData; // 0x18
	private static DelegateBridge __Hotfix0__RenderAppearanceType; // 0x20
	private static DelegateBridge __Hotfix0__RenderWeatherIcon; // 0x28
	private static DelegateBridge __Hotfix0_InitEnterAnim; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2567da4 VA: 0x7594b7fda4
	protected override Void DoOnInit() { }
	// RVA: 0x2567ef8 VA: 0x7594b7fef8
	protected override Void DoOnRecycle() { }
	// RVA: 0x2567f78 VA: 0x7594b7ff78
	protected override Void DoRenderBasicData(SandboxV2DungeonNodeViewModel nodeViewModel, SandboxV2DungeonViewModel dungeonViewModel) { }
	// RVA: 0x2568144 VA: 0x7594b80144
	protected override Void DoRenderData(SandboxV2DungeonNodeViewModel nodeViewModel, SandboxV2DungeonViewModel dungeonViewModel) { }
	// RVA: 0x256833c VA: 0x7594b8033c
	private Void _RenderAppearanceType(SandboxV2DungeonNodeViewModel nodeViewModel, SandboxV2DungeonViewModel dungeonViewModel) { }
	// RVA: 0x2568468 VA: 0x7594b80468
	private Void _RenderWeatherIcon(SandboxV2DungeonNodeViewModel nodeViewModel, SandboxV2DungeonViewModel dungeonViewModel) { }
	// RVA: 0x2568664 VA: 0x7594b80664
	protected override SandboxV2EnterAnimTween InitEnterAnim(SandboxV2DungeonNodeViewModel nodeViewModel, SandboxV2DungeonViewModel dungeonViewModel) { }
	// RVA: 0x2568724 VA: 0x7594b80724
	public Void .ctor() { }
	// RVA: 0x2568790 VA: 0x7594b80790
	private Void <>xLuaBaseProxy_DoOnInit() { }
	// RVA: 0x2568794 VA: 0x7594b80794
	private Void <>xLuaBaseProxy_DoOnRecycle() { }
	// RVA: 0x2568798 VA: 0x7594b80798
	private Void <>xLuaBaseProxy_DoRenderBasicData(SandboxV2DungeonNodeViewModel P0, SandboxV2DungeonViewModel P1) { }
	// RVA: 0x256879c VA: 0x7594b8079c
	private Void <>xLuaBaseProxy_DoRenderData(SandboxV2DungeonNodeViewModel P0, SandboxV2DungeonViewModel P1) { }
}
```