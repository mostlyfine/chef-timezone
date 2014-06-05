timezone Cookbook
=================
Manages the time zone configuration for a node.

Attributes
----------

e.g.
#### timezone::default
<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['timezone']</tt></td>
    <td>String</td>
    <td>the timezone name as defined in tzdata</td>
    <td><tt>UTC</tt></td>
  </tr>
</table>

Usage
-----
#### timezone::default
Set the "timezone" attribute to your desired timezone and include the "timezone" recipe in your node's run list:

e.g.
Just include `timezone` in your node's `run_list`:

```json
{
  "timezone": "Asia/Tokyo",
  "run_list": [
    "recipe[timezone]"
  ]
}
```

Contributing
------------
1. Fork the repository on Github
2. Create a named feature branch (like `add_component_x`)
3. Write your change
4. Write tests for your change (if applicable)
5. Run the tests, ensuring they all pass
6. Submit a Pull Request using Github

License and Authors
-------------------
MIT, Authors: mostlyfine
