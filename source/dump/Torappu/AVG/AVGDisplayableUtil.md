# AVGDisplayableUtil

**Namespace:** `Torappu.AVG`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGDisplayableUtil : IHotfixable
{
	private const String ANIMATE_TEXT_ALIAS; // 0x0
	private const String SPINE_TEXT_ALIAS; // 0x0
	private const String EFFECT_TEXT_ALIAS; // 0x0
	private const String BGEFFECT_TEXT_ALIAS; // 0x0
	private const String BG_TEXT_ALIAS; // 0x0
	private const String BG_OVERLAY_ALIAS; // 0x0
	private const String CHAR_OVERLAY_ALIAS; // 0x0
	private const Int32 BG_OVERLAY_CANVAS_ORDER; // 0x0
	private const Int32 CHAR_OVERLAY_CANVAS_ORDER; // 0x0
	private static DelegateBridge __Hotfix0_GenTypeFromRaw; // 0x0
	private static DelegateBridge __Hotfix0__GenTypeFromAlias; // 0x8
	private static DelegateBridge __Hotfix0_GenSlotFromRaw; // 0x10
	private static DelegateBridge __Hotfix0__GenSlotFromAlias; // 0x18
	private static DelegateBridge __Hotfix0_GetPrefabPathByType; // 0x20
	private static DelegateBridge __Hotfix0_GenerateParticleEffect; // 0x28
	private static DelegateBridge __Hotfix0__ProcessTimescale; // 0x30
	private static DelegateBridge __Hotfix0_GenerateImageHolder; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x3e53d34 VA: 0x759646bd34
	public static AVGDisplayableType GenTypeFromRaw(String rawType) { }
	// RVA: 0x3e5719c VA: 0x759646f19c
	private static AVGDisplayableType _GenTypeFromAlias(String rawAlias) { }
	// RVA: 0x3e55ae4 VA: 0x759646dae4
	public static AVGDisplaySlot GenSlotFromRaw(String rawSlot) { }
	// RVA: 0x3e572f0 VA: 0x759646f2f0
	private static AVGDisplaySlot _GenSlotFromAlias(String rawAlias) { }
	// RVA: 0x3e550cc VA: 0x759646d0cc
	public static String GetPrefabPathByType(AVGDisplayableType type, String name) { }
	// RVA: 0x3e5657c VA: 0x759646e57c
	public static ParticleEffect GenerateParticleEffect(ParticleEffect prefab, Transform container, Int32 layer, Vector3 rotate, Vector2 pos, AVGControllerSceneCanvas canvasEnum) { }
	// RVA: 0x3e573b4 VA: 0x759646f3b4
	private static Void _ProcessTimescale(Transform effectInstTrans) { }
	// RVA: 0x3e567b8 VA: 0x759646e7b8
	public static GameObject GenerateImageHolder(GameObject obj, Transform container) { }
	// RVA: 0x3e57608 VA: 0x759646f608
	public Void .ctor() { }
}
```