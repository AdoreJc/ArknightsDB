# Act5D1RuneStagePreview

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `Image _mapPreview`

- `Image _mapPreviewLarge`

- `GameObject _mapBlur`

- `Image _groupImg`

- `Text _pointCount`

- `GameObject _countDownPart`

- `Text _countDownText`

- `Text _mapDesc`

- `Text _stageName`

- `Text _stageCode`

- `Image _backImg`

- `DirectAssetLoader m_directAssetsLoader`


## Methods

- `Void OnClickMapDetail()`

- `Void _InitifNot()`

- `Void OnDestroy()`

- `Void OnCloseMapDetail()`

- `Void RenderInfo(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class Act5D1RuneStagePreview : MonoBehaviour, IHotfixable
{
	private Image _mapPreview; // 0x18
	private Image _mapPreviewLarge; // 0x20
	private GameObject _mapBlur; // 0x28
	private Image _groupImg; // 0x30
	private Text _pointCount; // 0x38
	private GameObject _countDownPart; // 0x40
	private Text _countDownText; // 0x48
	private Text _mapDesc; // 0x50
	private Text _stageName; // 0x58
	private Text _stageCode; // 0x60
	private Image _backImg; // 0x68
	private DirectAssetLoader m_directAssetsLoader; // 0x70
	private static DelegateBridge __Hotfix0_OnClickMapDetail; // 0x0
	private static DelegateBridge __Hotfix0__InitifNot; // 0x8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x10
	private static DelegateBridge __Hotfix0_OnCloseMapDetail; // 0x18
	private static DelegateBridge __Hotfix0_RenderInfo; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x31cc460 VA: 0x75957e4460
	public Void OnClickMapDetail() { }
	// RVA: 0x31cc4d0 VA: 0x75957e44d0
	private Void _InitifNot() { }
	// RVA: 0x31cc584 VA: 0x75957e4584
	private Void OnDestroy() { }
	// RVA: 0x31cc604 VA: 0x75957e4604
	public Void OnCloseMapDetail() { }
	// RVA: 0x31cc674 VA: 0x75957e4674
	public Void RenderInfo(String runeReId, String stageId) { }
	// RVA: 0x31cca14 VA: 0x75957e4a14
	public Void .ctor() { }
}
```