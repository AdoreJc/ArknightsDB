# ActMultiV3BoardPhotoView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `TwoStateToggle _filledToggle`

- `Text _numberText`

- `Text _titleDescText`

- `ActMultiV3PhotoView _contentView`

- `Transform _trackPointContainer`

- `GameObject _trackPointObj`

- `Boolean m_inited`

- `String m_cachedTemplateId`

- `String m_cachedInstId`

- `Int32 m_cachedPhotoTypeIdx`

- `UIStateFinder m_stateFinder`

- `GameObject m_trackPoint`


## Methods

- `Void Render(ActMultiV3PhotoViewModel)`

- `Void OnClickPhoto()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3BoardPhotoView : MonoBehaviour, IHotfixable
{
	private TwoStateToggle _filledToggle; // 0x18
	private Text _numberText; // 0x20
	private Text _titleDescText; // 0x28
	private ActMultiV3PhotoView _contentView; // 0x30
	private Transform _trackPointContainer; // 0x38
	private GameObject _trackPointObj; // 0x40
	private Boolean m_inited; // 0x48
	private String m_cachedTemplateId; // 0x50
	private String m_cachedInstId; // 0x58
	private Int32 m_cachedPhotoTypeIdx; // 0x60
	private UIStateFinder m_stateFinder; // 0x68
	private GameObject m_trackPoint; // 0x78
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClickPhoto; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3119bcc VA: 0x7595731bcc
	public Void Render(ActMultiV3PhotoViewModel model) { }
	// RVA: 0x311a4d4 VA: 0x75957324d4
	public Void OnClickPhoto() { }
	// RVA: 0x311a2c8 VA: 0x75957322c8
	private Void _InitIfNot() { }
	// RVA: 0x311a5b0 VA: 0x75957325b0
	public Void .ctor() { }
}
```