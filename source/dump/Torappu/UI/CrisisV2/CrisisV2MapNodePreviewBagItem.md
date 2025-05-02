# CrisisV2MapNodePreviewBagItem

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `UIAtlasImage _bagIcon`

- `UIAtlasObject _bagDimensionObject`

- `TwoStateToggle _bkgToggle`

- `UIAtlasImage _triangleDecor`

- `Text _currentScore`

- `Text _totalScore`

- `GameObject _completedDecor`

- `Color _iconUnselectColor`

- `Color _iconSelectColor`

- `Color _bkgUnselectColor`

- `Color _bkgSelectColor`

- `UIStateFinder m_stateFinder`

- `String m_cachedBagId`


## Methods

- `Void Render(CrisisV2MapBagModel, Boolean, CrisisV2Progress)`

- `Void OnBagIconClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2MapNodePreviewBagItem : MonoBehaviour, IHotfixable
{
	private const String TOTAL_SCORE_FORMAT; // 0x0
	private UIAtlasImage _bagIcon; // 0x18
	private UIAtlasObject _bagDimensionObject; // 0x20
	private TwoStateToggle _bkgToggle; // 0x28
	private UIAtlasImage _triangleDecor; // 0x30
	private Text _currentScore; // 0x38
	private Text _totalScore; // 0x40
	private GameObject _completedDecor; // 0x48
	private Color _iconUnselectColor; // 0x50
	private Color _iconSelectColor; // 0x60
	private Color _bkgUnselectColor; // 0x70
	private Color _bkgSelectColor; // 0x80
	private UIStateFinder m_stateFinder; // 0x90
	private String m_cachedBagId; // 0xa0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnBagIconClicked; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2c04f50 VA: 0x759521cf50
	public Void Render(CrisisV2MapBagModel bagModel, Boolean isAllSelected, CrisisV2Progress nodeProgress) { }
	// RVA: 0x2c051e4 VA: 0x759521d1e4
	public Void OnBagIconClicked() { }
	// RVA: 0x2c05360 VA: 0x759521d360
	public Void .ctor() { }
}
```