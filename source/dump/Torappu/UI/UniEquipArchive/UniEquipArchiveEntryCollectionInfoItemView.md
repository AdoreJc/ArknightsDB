# UniEquipArchiveEntryCollectionInfoItemView

**Namespace:** `Torappu.UI.UniEquipArchive`


## Fields

- `Text _txtTitle`

- `Text _txtCurCount`

- `CanvasGroup _canvasTotal`

- `Text _txtTotalCount`

- `GameObject _objSplitLine`

- `Boolean m_hasInited`

- `UniEquipArchiveCollectionInfoType m_cachedType`

- `FadeSwitchTween m_tweenTotalPart`


## Methods

- `Void Render(UniEquipArchiveEntryCollectionInfoItemViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquipArchive
public class UniEquipArchiveEntryCollectionInfoItemView : MonoBehaviour, IHotfixable
{
	private Text _txtTitle; // 0x18
	private Text _txtCurCount; // 0x20
	private CanvasGroup _canvasTotal; // 0x28
	private Text _txtTotalCount; // 0x30
	private GameObject _objSplitLine; // 0x38
	private Boolean m_hasInited; // 0x40
	private UniEquipArchiveCollectionInfoType m_cachedType; // 0x44
	private FadeSwitchTween m_tweenTotalPart; // 0x48
	private const String TOTAL_FORMAT; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x22ed9f0 VA: 0x75949059f0
	public Void Render(UniEquipArchiveEntryCollectionInfoItemViewModel infoItemViewModel) { }
	// RVA: 0x22edb90 VA: 0x7594905b90
	private Void _InitIfNot() { }
	// RVA: 0x22edee4 VA: 0x7594905ee4
	public Void .ctor() { }
}
```