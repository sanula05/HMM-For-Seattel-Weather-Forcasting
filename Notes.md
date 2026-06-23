# ADF Testisng block 
# print("ADF Statistic:", result[0])
# print("p-value:", result[1])
# print("Critical Values:")
# for key, value in result[4].items():
#     print(f"   {key}: {value}")  


# print(f"Transitions from {State_1} to {State_2}: {Counter_trans}, Total {State_1}: {Counter}")

# Heat Map code 
# states = ['snow', 'rain', 'drizzle', 'fog', 'sun']
# plt.figure(figsize=(8, 6))
# matrix = GetTransitionProb(Weather)

# sns.heatmap(
#     matrix,
#     annot=True,         
#     fmt=".2f",            
#     cmap="Blues",         
#     xticklabels=states,
#     yticklabels=states,
#     vmin=0, vmax=1,       
#     linewidths=0.5,
#     linecolor="white",
#     cbar_kws={"label": "Transition Probability"}
# )

# plt.title("Transition Matrix Heatmap", fontsize=14, pad=12)
# plt.xlabel("To State", fontsize=11)
# plt.ylabel("From State", fontsize=11)
# plt.xticks(rotation=45, ha="right")
# plt.yticks(rotation=0)
# plt.tight_layout()
# plt.savefig("transition_heatmap.png", dpi=150)
# plt.show()

*Seasonality and undoing transformations yet to be sorted 