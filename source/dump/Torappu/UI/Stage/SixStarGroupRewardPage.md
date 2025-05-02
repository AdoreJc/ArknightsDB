# SixStarGroupRewardPage

**Namespace:** `Torappu.UI.Stage`


## Fields

- `UIRenderTextureImage _imgBlurBkg`

- `String m_selectStageId`


## Properties

- `String selectStageId`


## Methods

- `String get_selectStageId()`

- `UIRenderTextureImage GetBlurBkg()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class SixStarGroupRewardPage : StateEnginePage, IFadeInPushWithBlurBkg, IHotfixable
{
	private UIRenderTextureImage _imgBlurBkg; // 0xe8
	private List`1 m_stageModelList; // 0xf0
	private String m_selectStageId; // 0xf8
	private static DelegateBridge __Hotfix0_get_stageModelList; // 0x0
	private static DelegateBridge __Hotfix0_get_selectStageId; // 0x8
	private static DelegateBridge __Hotfix0_OnCreate; // 0x10
	private static DelegateBridge __Hotfix0_GetBlurBkg; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public List`1 stageModelList { get; }
	public String selectStageId { get; }

	// RVA: 0x2f484b4 VA: 0x75955604b4
	public List`1 get_stageModelList() { }
	// RVA: 0x2f4851c VA: 0x759556051c
	public String get_selectStageId() { }
	// RVA: 0x2f48584 VA: 0x7595560584
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x2f48774 VA: 0x7595560774
	public UIRenderTextureImage GetBlurBkg() { }
	// RVA: 0x2f487dc VA: 0x75955607dc
	public Void .ctor() { }
	// RVA: 0x2f488a0 VA: 0x75955608a0
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
}
```