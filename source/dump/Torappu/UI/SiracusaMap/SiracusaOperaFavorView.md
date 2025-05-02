# SiracusaOperaFavorView

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `Text _currentCount`

- `Text _maxCount`

- `Text _remainTime`

- `Text _remainTimeUnit`

- `GameObject _remainTimePart`

- `GameObject _remainCountPart`


## Methods

- `Void Render(Int32, Int32, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaOperaFavorView : MonoBehaviour, IHotfixable
{
	private Text _currentCount; // 0x18
	private Text _maxCount; // 0x20
	private Text _remainTime; // 0x28
	private Text _remainTimeUnit; // 0x30
	private GameObject _remainTimePart; // 0x38
	private GameObject _remainCountPart; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x23fa2d4 VA: 0x7594a122d4
	public Void Render(Int32 totalCount, Int32 currentCount, Boolean isAllRelease) { }
	// RVA: 0x23fab44 VA: 0x7594a12b44
	public Void .ctor() { }
}
```