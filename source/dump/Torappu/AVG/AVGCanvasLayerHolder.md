# AVGCanvasLayerHolder

**Namespace:** `Torappu.AVG`


## Methods

- `SceneCanvasLayerConfig _FindCanvasOrderLayerConfigInternal(AVGControllerSceneCanvas)`

- `Void ShrinkSortingOrders(IList`1, AVGControllerSceneCanvas, Int32)`

- `Int32 CalculateOrderOffset(AVGControllerSceneCanvas, Int32)`

- `Int32 _CalculateNewLayer(SceneCanvasLayerConfig, Int32)`

- `Void _CheckOrderLimit(SceneCanvasLayerConfig, Int32)`

- `Void RefreshCanvasConfig()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGCanvasLayerHolder : IHotfixable
{
	public const Int32 SCENE_CANVAS_ORDERLAYER_GAP; // 0x0
	private SceneCanvasLayerConfig[] _configs; // 0x10
	private static DelegateBridge __Hotfix0__FindCanvasOrderLayerConfigInternal; // 0x0
	private static DelegateBridge __Hotfix0_ShrinkSortingOrders; // 0x8
	private static DelegateBridge __Hotfix0_CalculateOrderOffset; // 0x10
	private static DelegateBridge __Hotfix0__CalculateNewLayer; // 0x18
	private static DelegateBridge __Hotfix0__CheckOrderLimit; // 0x20
	private static DelegateBridge __Hotfix0_RefreshCanvasConfig; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x3e4957c VA: 0x759646157c
	private SceneCanvasLayerConfig _FindCanvasOrderLayerConfigInternal(AVGControllerSceneCanvas canvasName) { }
	// RVA: 0x3e49708 VA: 0x7596461708
	public Void ShrinkSortingOrders(IList`1 targets, AVGControllerSceneCanvas canvas, Int32 inCanvasLayer) { }
	// RVA: 0x3e49a84 VA: 0x7596461a84
	public Int32 CalculateOrderOffset(AVGControllerSceneCanvas canvas, Int32 inCanvasLayer) { }
	// RVA: 0x3e49948 VA: 0x7596461948
	private Int32 _CalculateNewLayer(SceneCanvasLayerConfig config, Int32 inCanvasLayer) { }
	// RVA: 0x3e499f8 VA: 0x75964619f8
	private Void _CheckOrderLimit(SceneCanvasLayerConfig config, Int32 newLayer) { }
	// RVA: 0x3e49c48 VA: 0x7596461c48
	public Void RefreshCanvasConfig() { }
	// RVA: 0x3e49e6c VA: 0x7596461e6c
	public Void .ctor() { }
}
```