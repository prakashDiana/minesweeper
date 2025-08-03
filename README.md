# minesweeper

SF Pro Rounded falls squarely on the side of **strict licensing**, not "chill" licensing.

Here's a breakdown of why its licensing is so restrictive:

* **Proprietary Apple Font:** SF Pro Rounded is a proprietary typeface owned by Apple. This means Apple holds the copyright and controls all aspects of its usage and distribution.
* **Highly Restrictive EULA:** The End User License Agreement (EULA) for these fonts is very specific and limited. It typically permits developers to use the fonts **only for creating mock-ups of user interfaces for software products running on Apple's operating systems** (iOS, macOS, watchOS, tvOS).
* **Prohibition on General Use:** The EULA expressly **prohibits** using the font for purposes outside of this narrow scope. This includes:
    * Embedding it as a web font on a general website.
    * Using it in logos, branding, or other marketing materials.
    * Incorporating it into software running on non-Apple platforms (e.g., Windows, Android, Linux).
* **Intellectual Property Protection:** Apple's San Francisco font family is a core part of its brand identity. By keeping its use tightly controlled, Apple protects its unique visual signature and maintains a premium, exclusive feel for its products.

In contrast, a "chill" license would be something like the **SIL Open Font License (OFL)**, which governs fonts like Latin Modern Roman. An OFL allows you to freely use, modify, and distribute the font for both personal and commercial projects, with very few restrictions.

Therefore, you should never assume you can use SF Pro Rounded freely. Its licensing is one of the most restrictive in the world of typefaces.

----------

Consolas falls on the side of **strict licensing**, but it is more permissive than SF Pro Rounded in practice. It occupies a middle ground, but its core license is proprietary, not "chill."

Here’s a detailed breakdown:

### Why Consolas is Not "Chill" (Strict Licensing)

1.  **Proprietary Microsoft Font:** Consolas is a proprietary typeface owned by **Microsoft Corporation**, designed by Luc(as) de Groot. It is a part of the ClearType Font Collection. This means it is not open-source, and its use is governed by a specific End User License Agreement (EULA) from Microsoft.

2.  **Bundled, Not Free for All:** Consolas is not a free, publicly available download for any use. It is primarily distributed as a bundled component of Microsoft products, including:
    * Windows (starting with Windows Vista)
    * Microsoft Office (since Office 2007)
    * Microsoft Visual Studio

3.  **Licensing is Product-Specific:** The right to use Consolas is tied to the license of the Microsoft product you acquired it with. The EULA for that product dictates how you can use the font. This is a classic characteristic of proprietary software licensing. For example, the Windows EULA allows you to use the font on that specific computer, but it doesn't give you a blanket right to redistribute it or embed it on a public website.

4.  **Requires Commercial Licensing for Broader Use:** If you want to use Consolas for purposes beyond what its bundled license allows—such as embedding it on a public website via `@font-face`, including it in a mobile application, or using it in a commercial product that doesn't include the font—you typically need to purchase a separate license from a font foundry that licenses it on Microsoft's behalf (e.g., MyFonts, Ascender Corporation).

### Why Consolas is More Permissive than SF Pro Rounded

While its core license is strict, Consolas is far more "chill" than SF Pro Rounded in its real-world application and perceived usage:

* **Widespread Availability:** Because it's bundled with so many widely-used Microsoft products, Consolas is a de facto standard on billions of Windows computers. This makes its presence and usage very common, whereas SF Pro is much more limited.
* **No Explicit "Mock-up Only" Restriction:** Unlike SF Pro Rounded's license, which explicitly limits its use to UI mockups for Apple platforms, the Consolas license tied to your Windows or Office installation generally allows you to use it for creating and printing documents.
* **De Facto Web Use:** Developers often use Consolas in CSS `font-family` declarations as a fallback for code blocks (`<pre>`, `<code>`) because they know it's a monospaced font available on most Windows systems.
* **Availability for Purchase:** You can legitimately purchase a license for web, app, or desktop use of Consolas from third-party vendors. This option simply does not exist for SF Pro Rounded.

**Conclusion:**

Consolas is a **strict, proprietary font** at its core. Its use is governed by a commercial license tied to the Microsoft software it's bundled with.

However, its widespread availability and the nature of its EULA make it much more **permissive and practically "chill"** for general document creation and even as a fallback for web code, especially when compared to the extremely rigid, brand-protecting license of SF Pro Rounded.
