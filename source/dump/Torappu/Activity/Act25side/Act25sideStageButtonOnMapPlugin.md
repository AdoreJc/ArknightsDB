# Act25sideStageButtonOnMapPlugin

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `UIAtlasObject _atlasObject`

- `UIAtlasImage _stageButtonImage`

- `String m_cachedStageId`


## Methods

- `SpriteRenderData _GetStageButtonSprite(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class Act25sideStageButtonOnMapPlugin : SimpleActivityStageButtonOnMapPlugin
{
	private UIAtlasObject _atlasObject; // 0x18
	private UIAtlasImage _stageButtonImage; // 0x20
	private String m_cachedStageId; // 0x28
	private static DelegateBridge __Hotfix0__GetStageButtonSprite; // 0x0
	private static DelegateBridge __Hotfix0_RenderStage; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x32721bc VA: 0x759588a1bc
	private SpriteRenderData _GetStageButtonSprite(String stageId) { }
	// RVA: 0x3272270 VA: 0x759588a270
	public override Void RenderStage(StageButtonOnMapHolder holder, StageViewModel viewModel, ZoneViewModel zoneViewModel, Boolean isSelected) { }
	// RVA: 0x3272380 VA: 0x759588a380
	public Void .ctor() { }
}
```