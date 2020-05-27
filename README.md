# NewYork

DANE // 

możemy wziąć lata : 2017 - 2019, miesiące : 03 - 06

moze sie przydac zeby wczytac duzo ramek danych pozniej:
(

files <- list.files(pattern = "file_.*csv")
df_list <- lapply(files,read_csv)
df <- bind_rows(df_list)
