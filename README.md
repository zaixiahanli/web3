# web3
# 查询账户余额
balance = web3.eth.get_balance('0xYourEthereumAddress')
print(web3.fromWei(balance, 'ether'))
