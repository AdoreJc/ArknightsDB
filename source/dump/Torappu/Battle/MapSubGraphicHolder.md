# MapSubGraphicHolder

**Namespace:** `Torappu.Battle`


## Fields

- `Vector3 _hideBakeOffset`


## Methods

- `Void EnableSubGraphic(String)`

- `Void DisableSubGraphic(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class MapSubGraphicHolder : MonoBehaviour, IHotfixable
{
	private SubGraphicSetting[] _settings; // 0x18
	private Vector3 _hideBakeOffset; // 0x20
	private static DelegateBridge __Hotfix0_get_settings; // 0x0
	private static DelegateBridge __Hotfix0_EnableSubGraphic; // 0x8
	private static DelegateBridge __Hotfix0_DisableSubGraphic; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public SubGraphicSetting[] settings { get; }

	// RVA: 0x407956c VA: 0x759669156c
	public SubGraphicSetting[] get_settings() { }
	// RVA: 0x40795d4 VA: 0x75966915d4
	public Void EnableSubGraphic(String subGraphicKey) { }
	// RVA: 0x4079af8 VA: 0x7596691af8
	public Void DisableSubGraphic(String subGraphicKey) { }
	// RVA: 0x4079da4 VA: 0x7596691da4
	public Void .ctor() { }
}
```