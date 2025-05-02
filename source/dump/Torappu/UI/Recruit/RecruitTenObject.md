# RecruitTenObject

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `UIAtlasImage _portrait`

- `Image _profession`

- `RectTransform _upState`

- `Image _starImage`

- `Single m_delta`


## Methods

- `Void ApplyData(GachaResult, Boolean)`

- `Vector2 <ApplyData>b__7_0()`

- `Void <ApplyData>b__7_1(Vector2)`

- `Vector2 <ApplyData>b__7_2()`

- `Void <ApplyData>b__7_3(Vector2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitTenObject : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _portrait; // 0x18
	private Image _profession; // 0x20
	private RectTransform _upState; // 0x28
	private Image _starImage; // 0x30
	private Sprite[] _starRaritySprites; // 0x38
	private RecruitTenRarityAdapter[] _rarityEffects; // 0x40
	private Single m_delta; // 0x48
	private const Int32 TIMES; // 0x0
	private static DelegateBridge __Hotfix0_ApplyData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2720a74 VA: 0x7594d38a74
	public Void ApplyData(GachaResult gachaResult, Boolean isOdd) { }
	// RVA: 0x27211d8 VA: 0x7594d391d8
	public Void .ctor() { }
	// RVA: 0x2721248 VA: 0x7594d39248
	private Vector2 <ApplyData>b__7_0() { }
	// RVA: 0x2721264 VA: 0x7594d39264
	private Void <ApplyData>b__7_1(Vector2 x) { }
	// RVA: 0x2721280 VA: 0x7594d39280
	private Vector2 <ApplyData>b__7_2() { }
	// RVA: 0x27212a8 VA: 0x7594d392a8
	private Void <ApplyData>b__7_3(Vector2 x) { }
}
```