# ArchiveTimelineItemText

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Int32 _maxWidth`

- `RectTransform _transformText`

- `RectTransform _transformBkg`

- `Text _text`

- `Boolean m_isInited`

- `String m_cachedText`


## Methods

- `Void _InitIfNot()`

- `Void _OnLayoutRebuilt()`

- `Void ApplyData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveTimelineItemText : MonoBehaviour, IHotfixable
{
	private const Int32 SPACING_LEFT; // 0x0
	private const Int32 SPACING_RIGHT; // 0x0
	private Int32 _maxWidth; // 0x18
	private RectTransform _transformText; // 0x20
	private RectTransform _transformBkg; // 0x28
	private Text _text; // 0x30
	private Boolean m_isInited; // 0x38
	private String m_cachedText; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__OnLayoutRebuilt; // 0x8
	private static DelegateBridge __Hotfix0_ApplyData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3085804 VA: 0x759569d804
	private Void _InitIfNot() { }
	// RVA: 0x3085990 VA: 0x759569d990
	private Void _OnLayoutRebuilt() { }
	// RVA: 0x3085adc VA: 0x759569dadc
	public Void ApplyData(String text) { }
	// RVA: 0x3085bb0 VA: 0x759569dbb0
	public Void .ctor() { }
}
```