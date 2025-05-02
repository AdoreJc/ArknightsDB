# SandboxV2NodeViewPortable

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Image _imgWeatherIcon`

- `Text _textNodeType`

- `Text _textNodeName`

- `SandboxV2CircleProgressBar _progressBar`

- `UIAtlasImage _imgTips`

- `UIAnimationLocation _enterAnim`

- `String m_cachedWeatherId`


## Methods

- `Void _RenderWeatherIcon(SandboxV2DungeonNodeViewModel, SandboxV2DungeonViewModel)`

- `Void <>xLuaBaseProxy_DoOnRecycle()`

- `Void <>xLuaBaseProxy_DoRenderBasicData(SandboxV2DungeonNodeViewModel, SandboxV2DungeonViewModel)`

- `Void <>xLuaBaseProxy_DoRenderData(SandboxV2DungeonNodeViewModel, SandboxV2DungeonViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2NodeViewPortable : SandboxV2AbstractNodeView
{
	private static readonly SandboxV2ConstructTipType[] CONCERNED_TIPS; // 0x0
	private Image _imgWeatherIcon; // 0xe8
	private Text _textNodeType; // 0xf0
	private Text _textNodeName; // 0xf8
	private SandboxV2CircleProgressBar _progressBar; // 0x100
	private UIAtlasImage _imgTips; // 0x108
	private UIAnimationLocation _enterAnim; // 0x110
	private String m_cachedWeatherId; // 0x120
	private static DelegateBridge __Hotfix0_DoOnRecycle; // 0x8
	private static DelegateBridge __Hotfix0_DoRenderBasicData; // 0x10
	private static DelegateBridge __Hotfix0_DoRenderData; // 0x18
	private static DelegateBridge __Hotfix0__RenderWeatherIcon; // 0x20
	private static DelegateBridge __Hotfix0_InitEnterAnim; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x25699ec VA: 0x7594b819ec
	protected override Void DoOnRecycle() { }
	// RVA: 0x2569a74 VA: 0x7594b81a74
	protected override Void DoRenderBasicData(SandboxV2DungeonNodeViewModel nodeViewModel, SandboxV2DungeonViewModel dungeonViewModel) { }
	// RVA: 0x2569b40 VA: 0x7594b81b40
	protected override Void DoRenderData(SandboxV2DungeonNodeViewModel nodeViewModel, SandboxV2DungeonViewModel dungeonViewModel) { }
	// RVA: 0x2569e50 VA: 0x7594b81e50
	private Void _RenderWeatherIcon(SandboxV2DungeonNodeViewModel nodeViewModel, SandboxV2DungeonViewModel dungeonViewModel) { }
	// RVA: 0x2569fa8 VA: 0x7594b81fa8
	protected override SandboxV2EnterAnimTween InitEnterAnim(SandboxV2DungeonNodeViewModel nodeViewModel, SandboxV2DungeonViewModel dungeonViewModel) { }
	// RVA: 0x256a078 VA: 0x7594b82078
	public Void .ctor() { }
	// RVA: 0x256a0f4 VA: 0x7594b820f4
	private static Void .cctor() { }
	// RVA: 0x256a188 VA: 0x7594b82188
	private Void <>xLuaBaseProxy_DoOnRecycle() { }
	// RVA: 0x256a18c VA: 0x7594b8218c
	private Void <>xLuaBaseProxy_DoRenderBasicData(SandboxV2DungeonNodeViewModel P0, SandboxV2DungeonViewModel P1) { }
	// RVA: 0x256a190 VA: 0x7594b82190
	private Void <>xLuaBaseProxy_DoRenderData(SandboxV2DungeonNodeViewModel P0, SandboxV2DungeonViewModel P1) { }
}
```