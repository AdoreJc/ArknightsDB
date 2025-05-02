# SandboxV2NodeViewHome

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `RectTransform _connectorPrefab`

- `RectTransform _connectorContainer`

- `SandboxV2CircleProgressBar _progressBar`

- `UIAtlasImage _imgTips`

- `UIAnimationLocation _enterAnimNormal`

- `UIAnimationLocation _enterAnimChallenge`

- `SandboxV2DungeonViewModel m_cachedDungeonViewModel`

- `SandboxV2DungeonNodeViewModel m_cachedNodeViewModel`

- `ConnectorPool m_connectorPool`


## Methods

- `Void <>xLuaBaseProxy_DoOnInit()`

- `Void <>xLuaBaseProxy_DoOnRecycle()`

- `Void <>xLuaBaseProxy_DoRenderPermanentData(SandboxV2DungeonNodeViewModel, SandboxV2DungeonViewModel)`

- `Void <>xLuaBaseProxy_DoRenderData(SandboxV2DungeonNodeViewModel, SandboxV2DungeonViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2NodeViewHome : SandboxV2AbstractNodeView
{
	private RectTransform _connectorPrefab; // 0xe8
	private RectTransform _connectorContainer; // 0xf0
	private SandboxV2CircleProgressBar _progressBar; // 0xf8
	private UIAtlasImage _imgTips; // 0x100
	private List`1 concernedTips; // 0x108
	private UIAnimationLocation _enterAnimNormal; // 0x110
	private UIAnimationLocation _enterAnimChallenge; // 0x120
	private Dictionary`2 m_cachedConnection; // 0x130
	private SandboxV2DungeonViewModel m_cachedDungeonViewModel; // 0x138
	private SandboxV2DungeonNodeViewModel m_cachedNodeViewModel; // 0x140
	private ConnectorPool m_connectorPool; // 0x148
	private static DelegateBridge __Hotfix0_DoOnInit; // 0x0
	private static DelegateBridge __Hotfix0_DoOnRecycle; // 0x8
	private static DelegateBridge __Hotfix0_DoRenderPermanentData; // 0x10
	private static DelegateBridge __Hotfix0_DoRenderData; // 0x18
	private static DelegateBridge __Hotfix0_InitEnterAnim; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2568b04 VA: 0x7594b80b04
	protected override Void DoOnInit() { }
	// RVA: 0x2568c54 VA: 0x7594b80c54
	protected override Void DoOnRecycle() { }
	// RVA: 0x2568ce4 VA: 0x7594b80ce4
	protected override Void DoRenderPermanentData(SandboxV2DungeonNodeViewModel nodeViewModel, SandboxV2DungeonViewModel dungeonViewModel) { }
	// RVA: 0x2568dcc VA: 0x7594b80dcc
	protected override Void DoRenderData(SandboxV2DungeonNodeViewModel nodeViewModel, SandboxV2DungeonViewModel dungeonViewModel) { }
	// RVA: 0x2569064 VA: 0x7594b81064
	protected override SandboxV2EnterAnimTween InitEnterAnim(SandboxV2DungeonNodeViewModel nodeViewModel, SandboxV2DungeonViewModel dungeonViewModel) { }
	// RVA: 0x2569140 VA: 0x7594b81140
	public Void .ctor() { }
	// RVA: 0x25691ac VA: 0x7594b811ac
	private Void <>xLuaBaseProxy_DoOnInit() { }
	// RVA: 0x25691b0 VA: 0x7594b811b0
	private Void <>xLuaBaseProxy_DoOnRecycle() { }
	// RVA: 0x25691b4 VA: 0x7594b811b4
	private Void <>xLuaBaseProxy_DoRenderPermanentData(SandboxV2DungeonNodeViewModel P0, SandboxV2DungeonViewModel P1) { }
	// RVA: 0x25691b8 VA: 0x7594b811b8
	private Void <>xLuaBaseProxy_DoRenderData(SandboxV2DungeonNodeViewModel P0, SandboxV2DungeonViewModel P1) { }
}
```