# Act27sideSpStagePlugin

**Namespace:** `Torappu.Activity.Act27side`


## Fields

- `UIAtlasObject _atlasObject`

- `UIAtlasImage _stageButtonBkg`

- `String m_cachedStageId`


## Methods

- `SpriteRenderData _GetStageButtonSprite(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act27side
public class Act27sideSpStagePlugin : SimpleActivityStageButtonOnMapPlugin, IHotfixable
{
	private UIAtlasObject _atlasObject; // 0x18
	private UIAtlasImage _stageButtonBkg; // 0x20
	private String m_cachedStageId; // 0x28
	private static DelegateBridge __Hotfix0__GetStageButtonSprite; // 0x0
	private static DelegateBridge __Hotfix0_RenderStage; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x326aacc VA: 0x7595882acc
	private SpriteRenderData _GetStageButtonSprite(String stageId) { }
	// RVA: 0x326ab80 VA: 0x7595882b80
	public override Void RenderStage(StageButtonOnMapHolder holder, StageViewModel viewModel, ZoneViewModel zoneViewModel, Boolean isSelected) { }
	// RVA: 0x326ac90 VA: 0x7595882c90
	public Void .ctor() { }
}
```