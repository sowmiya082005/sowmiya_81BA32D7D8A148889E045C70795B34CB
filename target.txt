def linearsearchProduct(productlist,targetproduct):
  indices = []
  for index,product in enumerate(productlist):
   if product == targetproduct:
    indices.append(index)

  return indices


#Example usage:
product = ["shoes","boot","loafer","shoes","sabdal","shoes"]
target = "shoes"
target2 = "apple"
result = linearsearchProduct(product,target2)
print(result)