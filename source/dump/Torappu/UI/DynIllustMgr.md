# DynIllustMgr

**Namespace:** `Torappu.UI`


## Fields

- `AbstractAssetLoader m_assetLoader`

- `RenderTexture m_rt`

- `Material m_mat`

- `Camera m_cam`

- `DynIllust m_activedIllust`

- `DynIllust m_illustInstance`


## Properties

- `Boolean pause`

- `AbstractAssetLoader assetLoader`


## Methods

- `Boolean get_pause()`

- `Void set_pause(Boolean)`

- `Void ClearAll()`

- `DynIllustView Load(CharUISkinStruct, Transform)`

- `Void Unload(DynIllust)`

- `DynIllust Active(DynIllustView)`

- `AbstractAssetLoader get_assetLoader()`

- `Void _InitDisplay()`

- `DynIllustView _CreateIllustView(DynIllust, Transform)`

- `Void _RefreshViewContent(DynIllustView)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class DynIllustMgr : SingletonMonoBehaviour`1, ISingletonNotAutoCreate
{
	private const Int32 LARGE_RT_SIZE; // 0x0
	public const Int32 RT_WIDTH; // 0x0
	public const Int32 RT_HEIGHT; // 0x0
	private AbstractAssetLoader m_assetLoader; // 0x18
	private RenderTexture m_rt; // 0x20
	private Material m_mat; // 0x28
	private Camera m_cam; // 0x30
	private DynIllust m_activedIllust; // 0x38
	private DynIllust m_illustInstance; // 0x40
	private static DelegateBridge __Hotfix0_get_pause; // 0x0
	private static DelegateBridge __Hotfix0_set_pause; // 0x8
	private static DelegateBridge __Hotfix0_ClearAll; // 0x10
	private static DelegateBridge __Hotfix0_Load; // 0x18
	private static DelegateBridge __Hotfix0_Unload; // 0x20
	private static DelegateBridge __Hotfix0_Active; // 0x28
	private static DelegateBridge __Hotfix0_OnInit; // 0x30
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x38
	private static DelegateBridge __Hotfix0_get_assetLoader; // 0x40
	private static DelegateBridge __Hotfix0__InitDisplay; // 0x48
	private static DelegateBridge __Hotfix0__CreateIllustView; // 0x50
	private static DelegateBridge __Hotfix0__RefreshViewContent; // 0x58
	private static DelegateBridge __Hotfix0__CreateRTForDynIllust; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public Boolean pause { get; set; }
	private AbstractAssetLoader assetLoader { get; }

	// RVA: 0x2111d08 VA: 0x7594729d08
	public Boolean get_pause() { }
	// RVA: 0x2111dd0 VA: 0x7594729dd0
	public Void set_pause(Boolean value) { }
	// RVA: 0x2111f04 VA: 0x7594729f04
	public Void ClearAll() { }
	// RVA: 0x21120ac VA: 0x759472a0ac
	public DynIllustView Load(CharUISkinStruct skin, Transform parent) { }
	// RVA: 0x211252c VA: 0x759472a52c
	public Void Unload(DynIllust res) { }
	// RVA: 0x21125c4 VA: 0x759472a5c4
	public DynIllust Active(DynIllustView view) { }
	// RVA: 0x2112ce8 VA: 0x759472ace8
	protected override Void OnInit() { }
	// RVA: 0x2112d4c VA: 0x759472ad4c
	protected override Void OnDestroy() { }
	// RVA: 0x21122e4 VA: 0x759472a2e4
	private AbstractAssetLoader get_assetLoader() { }
	// RVA: 0x2112934 VA: 0x759472a934
	private Void _InitDisplay() { }
	// RVA: 0x2112394 VA: 0x759472a394
	private DynIllustView _CreateIllustView(DynIllust res, Transform parent) { }
	// RVA: 0x2112850 VA: 0x759472a850
	private Void _RefreshViewContent(DynIllustView view) { }
	// RVA: 0x2112dd4 VA: 0x759472add4
	private static RenderTexture _CreateRTForDynIllust() { }
	// RVA: 0x2112f18 VA: 0x759472af18
	public Void .ctor() { }
}
```