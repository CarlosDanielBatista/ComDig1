library ieee;
use ieee.std_logic_1164.all;

entity VOTER is
port ( 
  i_1  :  in std_logic_vector(15 downto 0); -- Entrada 1 de dados
  i_2  :  in std_logic_vector(15 downto 0); -- Entrada 2 de dados
  i_3  :  in std_logic_vector(15 downto 0); -- Entrada 3 de dados
  o_1  :  out std_logic_vector(15 downto 0));-- Saida de dados
end VOTER;
architecture VOTER_ARCHITECTURE of VOTER is
begin
 process(i_1, i_2, i_3)
 begin
 
 o_1  <=  (i_1 and i_2) or (i_2 and i_3) or (i_1 and i_3); -- Checar se o dado é igual
 
 end process;
end VOTER_ARCHITECTURE;
