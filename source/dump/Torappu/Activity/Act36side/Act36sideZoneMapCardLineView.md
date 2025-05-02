# Act36sideZoneMapCardLineView

**Namespace:** `Torappu.Activity.Act36side`


## Fields

- `CanvasGroup _alphaHandler`

- `String m_stageId`


## Methods

- `Void Init(String, LineMeta)`

- `Void Render(ZoneViewModel)`

- `Void _RenderActive(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act36side
public class Act36sideZoneMapCardLineView : MonoBehaviour, IHotfixable
{
	private CanvasGroup _alphaHandler; // 0x18
	private String m_stageId; // 0x20
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__RenderActive; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x324a718 VA: 0x7595862718
	public Void Init(String stageId, LineMeta lineMeta) { }
	// RVA: 0x324a9a4 VA: 0x75958629a4
	public Void Render(ZoneViewModel zoneViewModel) { }
	// RVA: 0x324a90c VA: 0x759586290c
	private Void _RenderActive(Boolean isActive) { }
	// RVA: 0x324aa68 VA: 0x7595862a68
	public Void .ctor() { }
}
```