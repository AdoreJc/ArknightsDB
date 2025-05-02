# ActMultiV3PhotoView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Image _bgImage`

- `RectTransform _characterHolder`

- `ActMultiV3PhotoCharacter _characterSpinePrefab`

- `UIColorGraphic _characterGraphic`

- `String m_cachedPhotoBg`


## Methods

- `Void Render(String, String, List`1)`

- `Void _LoadCharacterSpines(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3PhotoView : MonoBehaviour, IHotfixable
{
	private Image _bgImage; // 0x18
	private RectTransform _characterHolder; // 0x20
	private ActMultiV3PhotoCharacter _characterSpinePrefab; // 0x28
	private UIColorGraphic _characterGraphic; // 0x30
	private String m_cachedPhotoBg; // 0x38
	private List`1 m_characters; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__LoadCharacterSpines; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x311a3d8 VA: 0x75957323d8
	public Void Render(String actId, String photoBg, List`1 charModels) { }
	// RVA: 0x311b574 VA: 0x7595733574
	private Void _LoadCharacterSpines(List`1 charModels) { }
	// RVA: 0x311b8f0 VA: 0x75957338f0
	public Void .ctor() { }
}
```