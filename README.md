## Heads
Search over 17,000 unique, artistic heads which are perfect for builders and servers with this awesome resource Heads.</br>
Quality, performance, and support are my priorities for this resource. Purchase it for $4.99 (sometimes cheaper with sales).
> **Tip:**  Please consider purchasing this resource on Spigot if you want to support me.
</br>

## Developers
Here is an example with built-in methods for developers that want to use the Heads developers API to code for other resources.
```ruby
# Check if Heads is installed and enabled.
if(Bukkit.getPluginManager().getPlugin("Heads") != null) {
Bukkit.broadcastMessage("Hooray!");
}

# How you would get the heads in any way.
Head getHead(int id)
Set<String> getCategories()
List<Head> getAllHeads()
List<Head> getCategoryHeads(String category)
void searchHeads(String query, Consumer<List<Head>> onResult)
void downloadHead(String playerName, Consumer<Head> consumer)

# How you would use the heads in any way.
int getId()
String getName()
String getCategory()
double getCost()
ItemStack getItem()
ItemStack getItem(String displayName)
```