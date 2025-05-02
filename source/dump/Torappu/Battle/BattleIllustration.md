# BattleIllustration

**Namespace:** `Torappu.Battle`


## Fields

- `Single _foldAlpha`

- `Vector2 _foldOffset`

- `Single _foldTime`

- `Image m_image`

- `Boolean m_fold`

- `Vector3 m_originPos`


## Properties

- `Boolean isValid`

- `Boolean folded`


## Methods

- `Boolean get_isValid()`

- `Boolean get_folded()`

- `Void set_folded(Boolean)`

- `Void SetImage(Image, Boolean)`

- `Void Clear()`

- `Void _FoldInternal(Boolean, Boolean)`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BattleIllustration : MonoBehaviour, IHotfixable
{
	private Single _foldAlpha; // 0x18
	private Vector2 _foldOffset; // 0x1c
	private Single _foldTime; // 0x24
	private Image m_image; // 0x28
	private Boolean m_fold; // 0x30
	private Vector3 m_originPos; // 0x34
	private static DelegateBridge __Hotfix0_get_isValid; // 0x0
	private static DelegateBridge __Hotfix0_get_folded; // 0x8
	private static DelegateBridge __Hotfix0_set_folded; // 0x10
	private static DelegateBridge __Hotfix0_SetImage; // 0x18
	private static DelegateBridge __Hotfix0_Clear; // 0x20
	private static DelegateBridge __Hotfix0__FoldInternal; // 0x28
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Boolean isValid { get; }
	public Boolean folded { get; set; }

	// RVA: 0x1c4e77c VA: 0x759426677c
	public Boolean get_isValid() { }
	// RVA: 0x1c4e814 VA: 0x7594266814
	public Boolean get_folded() { }
	// RVA: 0x1c4e87c VA: 0x759426687c
	public Void set_folded(Boolean value) { }
	// RVA: 0x1c4eae8 VA: 0x7594266ae8
	public Void SetImage(Image image, Boolean fold) { }
	// RVA: 0x1c4ec38 VA: 0x7594266c38
	public Void Clear() { }
	// RVA: 0x1c4e900 VA: 0x7594266900
	private Void _FoldInternal(Boolean fold, Boolean force) { }
	// RVA: 0x1c4ed28 VA: 0x7594266d28
	private Void OnDestroy() { }
	// RVA: 0x1c4ed90 VA: 0x7594266d90
	public Void .ctor() { }
}
```