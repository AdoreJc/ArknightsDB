# LargeBackgroundPanel

**Namespace:** `Torappu.AVG`


## Fields

- `RectTransform _initOffset`

- `RectTransform _offset`

- `Ease _fadeEase`

- `AVGSceneEffectManager m_effectManager`


## Methods

- `AbstractResRefCollecter DontInvoke_PlzImplInternalResRefCollector()`

- `Boolean _ExecuteImage(Command)`

- `Boolean _ExecuteVerticalBG(Command)`

- `Boolean _ExecuteGridBG(Command)`

- `Boolean _ExecuteImageTween(Command)`

- `Void _ResetPanel()`

- `Void _ResetImages()`

- `Void _ResetDisplayHandlers()`

- `Boolean _LoadImage(Image, String, Single, Single, Int32)`

- `String _PostDisplayKey(Int32)`

- `Void _BindCamEffectTarget()`

- `Void _BindPostDisplay(ref, String, Image, AVGSceneEffectManager)`

- `Void <>xLuaBaseProxy_OnStoryBegin(Story)`

- `Void <>xLuaBaseProxy_OnReset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class LargeBackgroundPanel : ExecutorComponent, IContainsResRefs
{
	private static readonly Dictionary`2 POSITION_INIT_FUNCTION; // 0x0
	private List`1 _images; // 0x50
	private RectTransform _initOffset; // 0x58
	private RectTransform _offset; // 0x60
	private Ease _fadeEase; // 0x68
	private List`1 m_largeBgDisplayHandlers; // 0x70
	private AVGSceneEffectManager m_effectManager; // 0x78
	private const Int32 MAX_IMAGE_COUNT; // 0x0
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x8
	private static DelegateBridge __Hotfix0_DontInvoke_PlzImplInternalResRefCollector; // 0x10
	private static DelegateBridge __Hotfix0__ExecuteImage; // 0x18
	private static DelegateBridge __Hotfix0__ExecuteVerticalBG; // 0x20
	private static DelegateBridge __Hotfix0__ExecuteGridBG; // 0x28
	private static DelegateBridge __Hotfix0__ExecuteImageTween; // 0x30
	private static DelegateBridge __Hotfix0_OnStoryBegin; // 0x38
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0x40
	private static DelegateBridge __Hotfix0_OnReset; // 0x48
	private static DelegateBridge __Hotfix0__ResetPanel; // 0x50
	private static DelegateBridge __Hotfix0__ResetImages; // 0x58
	private static DelegateBridge __Hotfix0__ResetDisplayHandlers; // 0x60
	private static DelegateBridge __Hotfix0__ResetImage; // 0x68
	private static DelegateBridge __Hotfix0__LoadImage; // 0x70
	private static DelegateBridge __Hotfix0__InitPositionUpperLeft; // 0x78
	private static DelegateBridge __Hotfix0__InitPositionCenter; // 0x80
	private static DelegateBridge __Hotfix0__InitPositionLowerCenter; // 0x88
	private static DelegateBridge __Hotfix0__InitPositionDefault; // 0x90
	private static DelegateBridge __Hotfix0__PostDisplayKey; // 0x98
	private static DelegateBridge __Hotfix0__BindCamEffectTarget; // 0xa0
	private static DelegateBridge __Hotfix0__BindPostDisplay; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0


	// RVA: 0x3e850fc VA: 0x759649d0fc
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x3e85368 VA: 0x759649d368
	public AbstractResRefCollecter DontInvoke_PlzImplInternalResRefCollector() { }
	// RVA: 0x3e8540c VA: 0x759649d40c
	private Boolean _ExecuteImage(Command command) { }
	// RVA: 0x3e86a18 VA: 0x759649ea18
	private Boolean _ExecuteVerticalBG(Command command) { }
	// RVA: 0x3e87a9c VA: 0x759649fa9c
	private Boolean _ExecuteGridBG(Command command) { }
	// RVA: 0x3e88e18 VA: 0x75964a0e18
	private Boolean _ExecuteImageTween(Command command) { }
	// RVA: 0x3e894dc VA: 0x75964a14dc
	public override Void OnStoryBegin(Story story) { }
	// RVA: 0x3e89734 VA: 0x75964a1734
	protected override Void ForceCommandEnd() { }
	// RVA: 0x3e897a8 VA: 0x75964a17a8
	public override Void OnReset() { }
	// RVA: 0x3e86630 VA: 0x759649e630
	private Void _ResetPanel() { }
	// RVA: 0x3e86494 VA: 0x759649e494
	private Void _ResetImages() { }
	// RVA: 0x3e89834 VA: 0x75964a1834
	private Void _ResetDisplayHandlers() { }
	// RVA: 0x3e8991c VA: 0x75964a191c
	private static Void _ResetImage(Image img) { }
	// RVA: 0x3e866e0 VA: 0x759649e6e0
	private Boolean _LoadImage(Image image, String imageName, Single width, Single height, Int32 idx) { }
	// RVA: 0x3e89d10 VA: 0x75964a1d10
	private static Vector2 _InitPositionUpperLeft(List`1 width, List`1 height) { }
	// RVA: 0x3e89e2c VA: 0x75964a1e2c
	private static Vector2 _InitPositionCenter(List`1 width, List`1 height) { }
	// RVA: 0x3e89ee0 VA: 0x75964a1ee0
	private static Vector2 _InitPositionLowerCenter(List`1 width, List`1 height) { }
	// RVA: 0x3e89fc4 VA: 0x75964a1fc4
	private static Vector2 _InitPositionDefault(List`1 width, List`1 height) { }
	// RVA: 0x3e89ad8 VA: 0x75964a1ad8
	private String _PostDisplayKey(Int32 idx) { }
	// RVA: 0x3e89578 VA: 0x75964a1578
	private Void _BindCamEffectTarget() { }
	// RVA: 0x3e89bb0 VA: 0x75964a1bb0
	private Void _BindPostDisplay(ref PostDisplayHandler handler, String key, Image image, AVGSceneEffectManager effectMgr) { }
	// RVA: 0x3e8a0a4 VA: 0x75964a20a4
	public Void .ctor() { }
	// RVA: 0x3e8a180 VA: 0x75964a2180
	private static Void .cctor() { }
	// RVA: 0x3e8a3b8 VA: 0x75964a23b8
	private Void <>xLuaBaseProxy_OnStoryBegin(Story P0) { }
	// RVA: 0x3e8a3c0 VA: 0x75964a23c0
	private Void <>xLuaBaseProxy_OnReset() { }
}
```