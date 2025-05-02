# UIMedalGroupFrame

**Namespace:** `Torappu.UI.Medal`


## Fields

- `String _groupId`

- `Image _imgMesh`


## Properties

- `String groupId`


## Methods

- `String get_groupId()`

- `Void Init(UIPage, Boolean)`

- `Boolean TryFindMedalPos(String, out)`

- `Void PopulateGraphics(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class UIMedalGroupFrame : MonoBehaviour, IHotfixable
{
	private String _groupId; // 0x18
	private List`1 _medalPosList; // 0x20
	private Image _imgMesh; // 0x28
	private static DelegateBridge __Hotfix0_get_groupId; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_LoadSuitBkgSprite; // 0x10
	private static DelegateBridge __Hotfix0_TryFindMedalPos; // 0x18
	private static DelegateBridge __Hotfix0_PopulateGraphics; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public String groupId { get; }

	// RVA: 0x278e0c8 VA: 0x7594da60c8
	public String get_groupId() { }
	// RVA: 0x278e130 VA: 0x7594da6130
	public Void Init(UIPage page, Boolean usePool) { }
	// RVA: 0x278e1d8 VA: 0x7594da61d8
	public static Sprite LoadSuitBkgSprite(UIPage page, String spriteId, Boolean usePool) { }
	// RVA: 0x278e4d4 VA: 0x7594da64d4
	public Boolean TryFindMedalPos(String medalId, out MedalPos retPos) { }
	// RVA: 0x278e610 VA: 0x7594da6610
	public Void PopulateGraphics(List`1 list) { }
	// RVA: 0x278e714 VA: 0x7594da6714
	public Void .ctor() { }
}
```