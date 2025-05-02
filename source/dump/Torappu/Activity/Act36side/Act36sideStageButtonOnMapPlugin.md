# Act36sideStageButtonOnMapPlugin

**Namespace:** `Torappu.Activity.Act36side`


## Fields

- `UIAtlasObject _atlasObject`

- `UIAtlasImage _stageButtonImage`

- `GameObject _panelTraining`

- `String m_cachedStageId`


## Methods

- `SpriteRenderData _GetStageButtonSprite(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act36side
public class Act36sideStageButtonOnMapPlugin : SimpleActivityStageButtonOnMapPlugin
{
	private UIAtlasObject _atlasObject; // 0x18
	private UIAtlasImage _stageButtonImage; // 0x20
	private GameObject _panelTraining; // 0x28
	private String m_cachedStageId; // 0x30
	private static DelegateBridge __Hotfix0__GetStageButtonSprite; // 0x0
	private static DelegateBridge __Hotfix0_RenderStage; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3248d28 VA: 0x7595860d28
	private SpriteRenderData _GetStageButtonSprite(String stageId) { }
	// RVA: 0x3248ddc VA: 0x7595860ddc
	public override Void RenderStage(StageButtonOnMapHolder holder, StageViewModel viewModel, ZoneViewModel zoneViewModel, Boolean isSelected) { }
	// RVA: 0x3248f08 VA: 0x7595860f08
	public Void .ctor() { }
}
```