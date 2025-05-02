# TemplateMissionCustomResHolder

**Namespace:** `Torappu.UI.TemplateMission`


## Fields

- `Sprite _titleImg`

- `Sprite _bgImg`

- `Sprite _coinImg`

- `Sprite _picRewardImg`

- `Vector2 _picRewardOffset`


## Methods

- `Sprite GetTitleImg()`

- `Sprite GetBgImg()`

- `Sprite GetCoinImg()`

- `Sprite GetPicRewardImg()`

- `Vector2 GetPicRewardOffset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateMission
public class TemplateMissionCustomResHolder : MonoBehaviour, IHotfixable
{
	private Sprite _titleImg; // 0x18
	private Sprite _bgImg; // 0x20
	private Sprite _coinImg; // 0x28
	private Sprite _picRewardImg; // 0x30
	private Vector2 _picRewardOffset; // 0x38
	private static DelegateBridge __Hotfix0_GetTitleImg; // 0x0
	private static DelegateBridge __Hotfix0_GetBgImg; // 0x8
	private static DelegateBridge __Hotfix0_GetCoinImg; // 0x10
	private static DelegateBridge __Hotfix0_GetPicRewardImg; // 0x18
	private static DelegateBridge __Hotfix0_GetPicRewardOffset; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x236b33c VA: 0x759498333c
	public Sprite GetTitleImg() { }
	// RVA: 0x236805c VA: 0x759498005c
	public Sprite GetBgImg() { }
	// RVA: 0x236a338 VA: 0x7594982338
	public Sprite GetCoinImg() { }
	// RVA: 0x2369480 VA: 0x7594981480
	public Sprite GetPicRewardImg() { }
	// RVA: 0x23694e8 VA: 0x75949814e8
	public Vector2 GetPicRewardOffset() { }
	// RVA: 0x236ba18 VA: 0x7594983a18
	public Void .ctor() { }
}
```