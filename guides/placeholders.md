# Placeholders

Placeholders allow you to personalize both the **subject** and **body** of your emails by dynamically inserting data, such as names, dates, or Excel ranges.

#### Example of a Placeholder

```
Hi {{Receiver_Name}},
```

#### Customizing Placeholders

The template sheet comes with some pre-set placeholders. You can change the placeholder names to suit your needs, just make sure they are always enclosed with double curly braces `{{ }}`. For example:

```
{{Customer_Name}} or {{Product_Name}}
```

#### Placeholders in the Subject

You can use placeholders not only in the email body but also in the **subject line**. For example:

```
Subject: Special Offer for {{Customer_Name}}!
```

This will be personalized for each recipient.

### Types of Placeholders

There are three types of placeholders that Gmail Blaster automatically detects: **Value**, **Date**, and **Excel Range**.

**1. Value**

A simple text or number value from a cell will be inserted directly into the email. For example:

```
Hi {{Customer_Name}},
```

If you have “John” in the corresponding cell, it will be replaced as:

```
Hi John,
```

**2. Date**

If the placeholder refers to a date, Gmail Blaster will automatically detect it.

**Important:** You must specify how you want the date displayed in the **SETTINGS** sheet. Even if the date cell in Excel is formatted differently, the display format should be set in the **SETTINGS**.\
For example:

```
{{Offer_End_Date}}
```

![](<../.gitbook/assets/image (10).png>)

**3. Excel Range**

To insert a table or range of cells, Gmail Blaster detects ranges formatted as `"SheetName!Range"`.\
**Example:**

```mathematica
{{Range}} --> "Data!A1:B3"
```

**Note:** Only the cell content will be inserted into the email. Charts, shapes, or other objects within the range will not be included.

#### Empty Placeholders

If a placeholder or Excel range is empty, Gmail Blaster will leave an empty space in the email where the placeholder was located.
