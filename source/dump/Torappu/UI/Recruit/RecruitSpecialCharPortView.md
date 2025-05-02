# RecruitSpecialCharPortView

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `RectTransform _container`

- `RecruitSpecialCharPortGroupView _prefabGroupView`

- `RecruitSpecialCharPortGroupView m_star6GroupView`

- `RecruitSpecialCharPortGroupView m_star5GroupView`


## Methods

- `Void Render(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitSpecialCharPortView : MonoBehaviour, IHotfixable
{
	private const String STAR_5_TITLE; // 0x0
	private const String STAR_6_TITLE; // 0x0
	private RectTransform _container; // 0x18
	private RecruitSpecialCharPortGroupView _prefabGroupView; // 0x20
	private RecruitSpecialCharPortGroupView m_star6GroupView; // 0x28
	private RecruitSpecialCharPortGroupView m_star5GroupView; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__GenerateCharGroupInput; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2711948 VA: 0x7594d29948
	public Void Render(String poolId) { }
	// RVA: 0x2711c80 VA: 0x7594d29c80
	private static Input _GenerateCharGroupInput(RarityRank rank, JObjectWrapper charDict, String title) { }
	// RVA: 0x2711dc8 VA: 0x7594d29dc8
	public Void .ctor() { }
}
```