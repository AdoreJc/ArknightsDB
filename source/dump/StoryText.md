# StoryText

**Namespace:** ` `


## Fields

- `String storyText`

- `DataUnlockType unLockType`

- `String unLockParam`

- `DataUnlockType showType`

- `String showParam`

- `String unLockString`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class StoryText
{
	public String storyText; // 0x10
	public DataUnlockType unLockType; // 0x18
	public String unLockParam; // 0x20
	public DataUnlockType showType; // 0x28
	public String showParam; // 0x30
	public String unLockString; // 0x38
	public List`1 patchIdList; // 0x40


	// RVA: 0x34a304c VA: 0x7595abb04c
	public Void .ctor() { }
	// RVA: 0x34a30c4 VA: 0x7595abb0c4
	public Void .ctor(String text, DataUnlockType unLockType, String unLockParam, String unLockString, List`1 patchIdList) { }
}
```